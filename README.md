1. จงประกาศการเรียกใช้font ชื่อ “Roboto” จาก Google Fonts

คำตอบ
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet" type="text/css">
	
<title>TEST!!</title>
	<style>
		h1 {
			font-family: 'Roboto', sans-serif;
		}
	</style>
</head>

<body>
	<h1> Sujira Ruangvesh</h1>
</body>
</html>
2. จงเขียนคำสั่งเพื่อกำหนด style ให้DIV id = “red-box” มีคุณสมบัติดังต่อไปนี้
- มีพ้ืนหลังสีแดงขอบสีเขียว
- มีขนาด 200 x 200 px
- วางอยู่ตำแหน่งแหน่งตรงกลางหน้าจอ

คำตอบ
<!doctype html>
<html>
<head>
<meta charset="utf-8">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300&display=swap" rel="stylesheet" type="text/css">
	
<title>TEST!!</title>
	<style>
		div{
			background-color: red;
			width: 200px;
			height: 200px;
		    border: 3px solid green;
		    margin: 50%;
			
		}
		
		
	</style>
</head>

<body>
	<section class="red-box" >
	<div class="red-box" >

	</div>
	</section>
</body>
</html>

3. จงเขียนคำสั่งเพี่อกำหนด style ให้DIV id = “response-box” มีคุณสมบัติดังต่อไปนี้
- มีความกวา้งและความสูงเท่ากับขนาดของ browser ในปัจจุบัน เมี่อ resize browser จะปรับเปลี่ยนขนาดเท่ากับขนาดปัจจุบันของ browser
- มีพี่นหลังสีเขียวเมี่อความกว้างของหน้าจอมีขนาด >= 512px
- มีพี่นหลังสีม่วงเมี่อความกว้างของหน้าจอมีขนาด >=720px
- มีพี่นหลังสีฟ้าเมี่อความกว้างของหน้าจอมีขนาด >=1024px

คำตอบ
<!doctype html>

<html>
<head>
<meta charset="utf-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
<link  href="main.css" rel="stylesheet" >
	
</head>

<body>
<nav>
	WEB SITE
	</nav>
<main>

	<aside>
		SUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESH
			</aside>
		<article>
		SUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESHSUJIRA RUANGVESH	
			</article>
	
	

	</main>
<footer>
	copy right 2021.
	</footer>	
</body>
</html>


*{
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}



nav{
	padding: 15px;
	background-color: aqua;
	
	
}


main{
	display: flex;
	padding: 15px;
	background-color: burlywood;
	justify-content: space-between;
	height: 100vh;
}
ื

aside{
	width:  70%;
	background-color: yellowgreen;
}

article{
	width:  70%;
	background-color: cadetblue;
}


footer{
	padding: 15px;
	text-align: center;
	background-color: darkred;
}

@media  screen and (min-width: 512px)  {
	main{
		flex-direction: column;
		
		background-color: green;
	}
	
	aside{
		
		width: 100%;
		height: 100%;
		
	}
	
	article{
		
		width: 100%;
        height: 100%;
	}
		}
		
		
@media  screen and (min-width: 720px)  {
	main{
		flex-direction: column;
		background-color: purple;
	}
	
	aside{
		width: 100%;
	}
	
	article{
		width: 100%;
		height: 100%;
	}
		}
		
@media  screen and (min-width: 1024px)  {
	main{
		flex-direction: column;
		background-color: blue;
	}
	aside{
		width: 100%;
	}
	
	article{
		width: 100%;
		height: 100%;
	}
		}
		

4. จงเขียนคำสั่งเพี่อกำหนดให้style ให้DIV id = “bg-box” มีคุณสมบัติดังต่อไปน้ี
- กำหนดพื้นหลังโดยใชรู้ปภาพที่ชื่อวา่ “bg.jpg”
- กำหนดความกว้าง 300 x 300px
- รูปพื้นหลังแสดงได้พอดีกับขนาดของ DIV
- ไม่แสดงรูปภาพพื้นหลังแบบวนซ้ำ (repeat)
