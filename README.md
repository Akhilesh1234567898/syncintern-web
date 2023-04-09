# syncintern-web
<!DOCTYPE html>
<html>
<head>
	<title>Product Landing Page</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		/* Add your styles here */
	</style>
</head>
<body>

	<header>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">Features</a></li>
				<li><a href="#">Pricing</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
	</header>

	<main>

		<section id="hero">
			<h1>Product Name</h1>
			<p>Short description of the product.</p>
			<a href="#" class="cta-button">Buy Now</a>
		</section>

		<section id="features">
			<h2>Features</h2>
			<ul>
				<li>Feature 1</li>
				<li>Feature 2</li>
				<li>Feature 3</li>
			</ul>
		</section>

		<section id="pricing">
			<h2>Pricing</h2>
			<ul>
				<li>Option 1 - $19.99</li>
				<li>Option 2 - $29.99</li>
				<li>Option 3 - $39.99</li>
			</ul>
		</section>

		<section id="contact">
			<h2>Contact Us</h2>
			<form>
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required><br>

				<label for="email">Email:</label>
				<input type="email" id="email" name="email" required><br>

				<label for="message">Message:</label>
				<textarea id="message" name="message" required></textarea><br>

				<input type="submit" value="Submit">
			</form>
		</section>

	</main>

	<footer>
		<p>&copy; 2023 Product Name. All rights reserved.</p>
	</footer>

</body>
</html>
