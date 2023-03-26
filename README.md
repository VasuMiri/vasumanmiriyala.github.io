!DOCTYPE html>
<html>
<head>
	<title>Vasuman Miriyala</title>
	<style>
		body {
			background-color: white;
			font-family: Helvetica, Arial, sans-serif;
			text-align: center;
		}
		h1 {
			color: black;
			font-size: 60px;
			font-weight: bold;
			margin-top: 200px;
			position: relative;
			animation: type 3s steps(30);
			overflow: hidden;
			display: inline-block;
		}
		h1::after {
			content: "|";
			position: absolute;
			right: 0;
			animation: caret 0.5s step-end infinite;
		}
		img {
			height: 50px;
			margin: 20px;
			cursor: pointer;
		}
		img:hover {
			opacity: 0.8;
		}
		.logo-container {
			display: flex;
			justify-content: center;
		}
		@keyframes type {
			from { width: 0; }
		}
		@keyframes caret {
			50% { opacity: 0; }
		}
	</style>
</head>
<body>
	<h1>Vasuman Miriyala</h1>
	<div class="logo-container">
		<a href="https://www.linkedin.com/in/vasuman-miriyala-314063267/"><img src="linkedin.png" alt="LinkedIn"></a>
		<a href="mailto:vasumanmiriyala@gmail.com"><img src="gmail.png" alt="Gmail"></a>
		<a href="https://discord.gg/wkd6CyjSR4"><img src="discord.png" alt="Discord"></a>
	</div>
</body>
</html>
