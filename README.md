
# welcome to my website

my website

<html>

	<head>

		<meta charset='UTF-8'>

		

		<title>Simple Loader</title>

		

		<style>

		.content {display:none;}

		.preload { width:150px;

			height: 200px;

			position: fixed;

			top: 30%;

			left: 20%;

		}

		</style>

		<script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>

		<script>

		$(function() {

			$(".preload").fadeOut(2500, 

		function() {

			$(".content").fadeIn(1000);

		});

		});

		</script>

	</head>

	<body>

		<div class="preload"><img src="https://user-images.githubusercontent.com/79648523/135600276-faa55211-5695-403e-801c-12dbbd869cb2.gif"></div>

		<div class="content">

			HELLO WORLD MY NAME IS BIG 

	</div>

	</body>

</html>

<!-- ref : SmallEnvelop.com -->

<!-- https://smallenvelop.com/display-loading-icon-page-loads-completely/ -->
