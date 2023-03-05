<!DOCTYPE html>
<html>
<head>
	<title>Pizza Maker</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<div class="pizza-box">
			<div class="empty-circle"></div>
			<div class="pizza-base-list">
				<h2>Select a pizza base:</h2>
				<select id="base-list">
					<option value="none">Select a base</option>
					<option value="plain">Plain</option>
					<option value="garlic">Garlic</option>
					<option value="tomato">Tomato</option>
				</select>
			</div>
			<div class="ingredients-list">
				<h2>Select ingredients:</h2>
				<div class="ingredient" id=><img src="https://www.google.com/search?q=transparent+pepperoni&rlz=1C1ONGR_enIN989IN989&oq=transparent+pepperoni&aqs=chrome..69i57j0i22i30l2j0i390l4j69i60.16235j0j15&sourceid=chrome&ie=UTF-8#imgrc=5PmovWbepyiMsM&imgdii=rzHHtmNsvtK0OM"><p>Pepperoni</p></div>
				<div class="ingredient" id="mushroom"><img src="https://www.google.com/search?q=pizza+mushroom+png&tbm=isch&ved=2ahUKEwii39C-tcX9AhUQoNgFHdWWCIYQ2-cCegQIABAA&oq=pizza+Mushroom&gs_lcp=CgNpbWcQARgCMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDoHCAAQsQMQQzoECAAQQzoICAAQgAQQsQNQ-AVYgStg-z5oAXAAeACAAbEBiAH-BJIBAzAuNJgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=Rd8EZOKoBpDA4t4P1a2isAg&bih=552&biw=1280&rlz=1C1ONGR_enIN989IN989#imgrc=dGBG4Y_oDOKwiM"><p>Mushroom</p></div>
				<div class="ingredient" id="onion"><img src="https://www.google.com/search?q=pizza+ingredients+png&rlz=1C1ONGR_enIN989IN989&ei=pt8EZP_HIZCr4-EPzfKbmAY&ved=0ahUKEwj_sozttcX9AhWQ1TgGHU35BmMQ4dUDCA8&uact=5&oq=pizza+ingredients+png&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIFCAAQgAQyBggAEBYQHjIFCAAQhgMyBQgAEIYDMgUIABCGAzoKCAAQRxDWBBCwAzoHCAAQsAMQQzoNCAAQ5AIQ1gQQsAMYAToMCC4QyAMQsAMQQxgCOg8ILhDUAhDIAxCwAxBDGAI6CAgAEIAEELEDOgQIABBDOgUILhCABEoECEEYAFDSBli3GWDGIWgBcAF4AIABuAGIAasFkgEDMC40mAEAoAEByAERwAEB2gEGCAEQARgJ2gEGCAIQARgI&sclient=gws-wiz-serp#imgrc=1Qj6gqgMr1Qp0M"><p>Onion</p></div>
				<div class="ingredient" id="olive"><img src="https://www.google.com/search?q=pizza+oliveshttps%3A%2F%2Fwww.google.com%2Fsearch%3Fq%3Dpizza%2Bingredients%2Bpng%26rlz%3D1C1ONGR_enIN989IN989%26ei%3Dpt8EZP_HIZCr4-EPzfKbmAY%26ved%3D0ahUKEwj_sozttcX9AhWQ1TgGHU35BmMQ4dUDCA8%26uact%3D5%26oq%3Dpizza%2Bingredients%2Bpng%26gs_lcp%3DCgxnd3Mtd2l6LXNlcnAQAzIFCAAQgAQyBggAEBYQHjIFCAAQhgMyBQgAEIYDMgUIABCGAzoKCAAQRxDWBBCwAzoHCAAQsAMQQzoNCAAQ5AIQ1gQQsAMYAToMCC4QyAMQsAMQQxgCOg8ILhDUAhDIAxCwAxBDGAI6CAgAEIAEELEDOgQIABBDOgUILhCABEoECEEYAFDSBli3GWDGIWgBcAF4AIABuAGIAasFkgEDMC40mAEAoAEByAERwAEB2gEGCAEQARgJ2gEGCAIQARgI%26sclient%3Dgws-wiz-serp%23imgrc%3D1Qj6gqgMr1Qp0Mng&tbm=isch&ved=2ahUKEwjPksGWtsX9AhVeDbcAHRUACqkQ2-cCegQIABAA&oq=pizza+oliveshttps%3A%2F%2Fwww.google.com%2Fsearch%3Fq%3Dpizza%2Bingredients%2Bpng%26rlz%3D1C1ONGR_e"><p>Olive</p></div>
			</div>
			<button id="reset-btn">Reset</button>
		</div>
	</div>
	<script src="app.js"></script>
</body>
</html>

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	font-family: Arial, sans-serif;
}

.container {
	width: 100%;
	height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
}

.pizza-box {
	width: 50%;
	height: 80%;
	background-color: #f5f5f5;
	border-radius: 10px;
	box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
	display: flex;
	flex-direction: column;
	justify-content: space-between;
	align-items: center;
	padding: 20px;
}

.empty-circle {
	width: 300px;
	height: 300px;
	border: 2px dashed gray;
	border-radius: 50%;
	display: flex;
	justify-content: center;
	align-items: center;
	margin-bottom: 20px;
}

.pizza-base-list {
	display: flex;
	flex-direction: column;
	align-items: center;
}

.ingredients-list {
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}

.ingredient {
	width: 23%;
	height: 150px;
	background-color: white;
	border: 2px solid gray;
	border-radius: 5px
