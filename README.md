<link rel="icon" href="favicon.ico" type="image/x-icon"/>

# **Welcome to my website!**
## This Webstie is a Test
<br />
<br />
#██████╗░░█████╗░██╗░░░░░██████╗░██████╗░██╗░░░██╗███╗░░░███╗░██████╗
#██╔══██╗██╔══██╗██║░░░░░██╔══██╗██╔══██╗██║░░░██║████╗░████║██╔════╝
#██║░░██║██║░░██║██║░░░░░██║░░██║██████╔╝██║░░░██║██╔████╔██║╚█████╗░
#██║░░██║██║░░██║██║░░░░░██║░░██║██╔══██╗██║░░░██║██║╚██╔╝██║░╚═══██╗
#██████╔╝╚█████╔╝███████╗██████╔╝██║░░██║╚██████╔╝██║░╚═╝░██║██████╔╝
#╚═════╝░░╚════╝░╚══════╝╚═════╝░╚═╝░░╚═╝░╚═════╝░╚═╝░░░░░╚═╝╚═════╝░
<br />
<br />
<br />
<br />
Thank you for visiting my website
<br />
<br />
<button onclick="myFunction()">Click Me!</button>

<script>
function myFunction() {
  alert("Thanks for visiting my website!");
}
</script>
<br />
<br />
About:
<br />
I am a student who creates and published video games. A software engineer. I created a test website for furture programming. I created this domain/website using github pages. This was made with javascript. I have published many games across different platoforms.
<br />
<br />
Here are some photos of my creations:
<br />
<br />
<img width="200" alt="logo 4 good game" src="https://user-images.githubusercontent.com/125189307/229464201-1a753459-1f34-4d47-95f6-9c5a55191937.PNG">
<br />
<br />
<img width="200" alt="th (2)" src="https://user-images.githubusercontent.com/125189307/229464301-aa91a037-d4c2-4b2c-b857-6323902e66fb.PNG">
<br />
<br />
<img width="200" alt="my room" src="https://user-images.githubusercontent.com/125189307/229464582-6b47ad20-0f9d-44b4-91be-5ab497170fd0.png">
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
Thank you for visiting my website
<br />
<br />
<br />
<iframe width="560" height="315" src="https://www.youtube.com/embed/tS92P9PWNfU" 
frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />
<html>
<head>
	<title>Click Me!</title>
	<style>
		/* Styling for the popup container */
		.popup {
			display: none; /* Hidden by default */
			position: fixed; /* Stay in place */
			z-index: 1; /* Sit on top */
			left: 0;
			top: 0;
			width: 100%; /* Full width */
			height: 100%; /* Full height */
			overflow: auto; /* Enable scroll if needed */
			background-color: rgba(0,0,0); /* Black w/ opacity */
		}
		
		/* Styling for the popup content */
		.popup-content {
			background-color: #000000;
			margin: 15% auto; /* 15% from the top and centered */
			padding: 20px;
			border: 1px solid #888;
			width: 80%; /* Could be more or less, depending on screen size */
		}
		
		/* Styling for the close button */
		.close {
			color: #aaa;
			float: right;
			font-size: 28px;
			font-weight: bold;
		}
		
		.close:hover,
		.close:focus {
			color: black;
			text-decoration: none;
			cursor: pointer;
		}
	</style>
</head>
<body>

	<h2>You have been hacked</h2>

	<!-- The button that triggers the popup -->
	<button onclick="openPopup()">Open Popup</button>

	<!-- The popup container -->
	<div id="myPopup" class="popup">
		<!-- Popup content -->
		<div class="popup-content">
			<span class="close" onclick="closePopup()">&times;</span>
			<p>You have been hacked!</p>
			<p>Click the X to close it.</p>
		</div>
	</div>

	<script>
		// Get the popup container
		var popup = document.getElementById("myPopup");

		// Function to open the popup
		function openPopup() {
			popup.style.display = "block";
		}

		// Function to close the popup
		function closePopup() {
			popup.style.display = "none";
		}
	</script>

</body>
</html>


