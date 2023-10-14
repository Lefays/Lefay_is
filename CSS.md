body {
	background: linear-gradient(to bottom, #000000, #fa00fa);
	margin: 0;
	padding: 0;
	font-family: Arial, sans-serif;
}

.container {
	position: absolute;
	top: 50%;
	left: 50%;
	transform: translate(-50%, -50%);
	text-align: center;
	color: white;
	margin-top: 5em;
}

h1 {
	font-size: 4em;
	margin: 0;
}

p {
	font-size: 1.5em;
	margin-bottom: 2.5em;
}

.button-container {
	display: flex;
	flex-wrap: wrap;
	justify-content: center;
	margin-top: 2em;
}

.button {
	padding: 1.2em 3.5em;
	margin: 2.1em;
	background-color: white;
	color: #5b0f7e;
	border: none;
	border-radius: 2em;
	text-decoration: none;
	font-size: 1.2em;
	cursor: pointer;
	transition: all 0.3s ease-in-out;
	box-shadow: 0px 0px 10px rgba(0,0,0,0.4);
}

.button:hover {
	transform: scale(1.2) rotate(10deg);
	box-shadow: 8px 8px 8px rgba(0,0,0,0.4);
	color: #5b0f7e;
}

.button:focus {
	outline: none;
	box-shadow: 0 0 5px #5b0f7e;
}

.button[data-image-url] {
	background-image: var(--image-url);
	background-size: cover;
	background-position: center center;
	color: white;
}

.button[data-image-url]:hover {
	background-color: rgba(0, 0, 0, 0.5);
}
