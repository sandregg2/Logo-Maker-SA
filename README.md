# Module 10 Challenge
- This is a README for our 10th challenge for our coding bootcamp
## Description of challenge 
- Your task is to build a Node.js command-line application that takes in user input to generate a logo and save it as an [SVG file](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics). The application prompts the user to select a color and shape, provide text for the logo, and save the generated SVG to a `.svg` file.
## Table of Contents
* [Installation](#installation)
* [Usage](#usage)
* [Demo video](#Demo-video)
* [Screenshot of logo from demo](#Screenshot-from-demo)
## Installation
1. Clone/download this repo to your computer
2. Open this repo in VSCode
3. Run the terminal and navigate this this repo in your files 
4. Type in "npm install" and let it finish 
5. Type in 'node index.js' and you will be prompted in the terminal 
6. Fillout with your responses 
7. Logo is created and should go into the repo as 'logo.svg'
## Usage
- Create a logo with shapes and colors using node in the terminal
## Demo Video
- https://watch.screencastify.com/v/F50PTvEHg03rItpUuZE2
## Screenshot from demo
- <svg version="1.1" width="300" height="200" xmlns="http://www.w3.org/2000/svg"><g>Square<rect x="73" y="40" width="160" height="160" fill="Black"/><text x="150" y="130" text-anchor="middle" font-size="40" fill="Red">SAA</text></g><!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>
</svg>
