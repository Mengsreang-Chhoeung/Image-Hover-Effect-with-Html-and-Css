### Image-Hover-Effect-with-Html-and-Css
#### Enjoy coding with html and css...

លំហាត់ខាងក្រោមនេះ ទាមទារឲ្យអ្នកមានចំណេះដឹងទាក់ទងនឹង:
- HTML
- CSS
  - Position
  - Transform 2D and 3D
  - Flexbox

# លំហាត់ Image Hover Effect
![Thumbnail](/images/1.jpg)
# កូដ HTML:
```javascript
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<title>Image Hover Effect</title>
	<link rel="stylesheet" type="text/css" href="css/style2.css">
</head>
<body>
	<div class="image">
		<!-- nth-child(1) -->
		<img src="images/image.jpeg">
		<!-- nth-child(2) -->
		<img src="images/noise.png">
	</div>
</body>
</html>
```
# កូដ CSS:
```javascript
body{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	height: 100vh;
	display: flex;
	justify-content: center;
	align-items: center;
}

.image{
	width: 300px;
	height: 400px;
	cursor: pointer;
	position: relative;
	overflow: hidden;
}

.image img:nth-child(1){
	width: 100%;
	height: 100%;
	transition: 4s;
	position: absolute;
	top: 0;
	left: 0;
}

.image:hover img:nth-child(1){
	transform: translateX(50px);
	opacity: 0;
	filter: blur(10px);
	transform: rotate(-40deg);
	transition-delay: 1s; 
}

.image img:nth-child(2){
	width: 1200px;
	height: 100%;
	transform: translateX(300px) scaleX(0);
	transition: 8s;
}

.image:hover img:nth-child(2){
	transform: translateX(-300px) scaleX(1);
}
```
[Facebook-MengSreang Channel](https://www.facebook.com/mengsreangchannel)

[Facebook-CodeIsMine](https://www.facebook.com/CodeIsMine)

[YouTube-MengSreang Channel](https://www.youtube.com/channel/UCE6UmKNi-bYNWwOBUYoT-yQ)

[YouTube-CodeIsMine](https://www.youtube.com/channel/UCBKsUkGih9kdXcrz54zNH1w)

### អរគុណច្រើន សំណាងល្អ!🙏
