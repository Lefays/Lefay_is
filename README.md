<html>
<head>
	<title>Website title</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div id="particles-js"></div>
	<div class="container">
		<h1>Hello!</h1>
		<p>My name is Lefay and I work as a web designer and coder. Currently, I am learning C# to develop games. I can speak Russian, English and Swedish.</p>
		<div class="button-container">
			<a href="https://www.example.com" class="button" target="_blank">Site</a>
			<a href="https://www.example.co" class="button" target="_blank">Site</a>
			<a href="https://www.example.co" class="button" target="_blank">Site</a>
		</div>
	</div>

	<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
	<script>
		particlesJS("particles-js", {
			"particles": {
				"number": {
					"value": 300,
					"density": {
						"enable": true,
						"value_area": 800
					}
				},
				"color": {
					"value": "#5b0f7e"
				},
				"shape": {
					"type": "circle",
					"stroke": {
						"width": 0,
						"color": "#000000"
					},
					"polygon": {
						"nb_sides": 5
					},
					"image": {
						"src": "img/github.svg",
						"width": 100,
						"height": 100
					}
				},
				"opacity": {
					"value": 1,
					"random": true,
					"anim": {
						"enable": true,
						"speed": 1,
						"opacity_min": 0,
						"sync": false
					}
				},
				"size": {
					"value": 3,
					"random": true,
					"anim": {
						"enable": false,
						"speed": 4,
						"size_min": 0.3,
						"sync": false
					}
				},
				"line_linked": {
					"enable": false,
					"distance": 150,
					"color": "#ffffff",
					"opacity": 0.4,
					"width": 1
				},
				"move": {
					"enable": true,
					"speed": 1,
					"direction": "none",
					"random": true,
					"straight": false,
					"out_mode": "out",
					"bounce": false,
					"attract": {
						"enable": false,
						"rotateX": 600,
						"rotateY": 600
					}
				}
			},
			"interactivity": {
				"detect_on": "canvas",
				"events": {
					"onhover": {
						"enable": true,
						"mode": "bubble"
					},
					"onclick": {
						"enable": true,
						"mode": "repulse"
					},
					"resize": true
				},
				"modes": {
					bubble: {
					    "distance": 250,
					    "size": 0,
					    "duration": 2,
					    "opacity": 0,
					    "speed": 3
				    },
				    repulse: {
				        "distance": 200,
				        "duration": 0.4
				    },
				    push: {
				        "particles_nb": 4
				    },
				    remove: {
				        "particles_nb": 2
				    }
				}
			},
			retina_detect: true
	    });
    </script>

    <style>
    	body {
			background: linear-gradient(to bottom, #000004, #41024b);
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
    </style>
</body>
</html>

