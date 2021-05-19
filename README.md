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
- มีพื้นหลังสีแดงขอบสีเขียว
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
            position: absolute;
            top: 50%;
            left: 50%;
            margin-top: -100px;
            margin-left: -100px;
			
			
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
- กำหนดพื้นหลังโดยใช้รูปภาพที่ชื่อว่า “bg.jpg”
- กำหนดความกว้าง 300 x 300px
- รูปพื้นหลังแสดงได้พอดีกับขนาดของ DIV
- ไม่แสดงรูปภาพพื้นหลังแบบวนซ้ำ (repeat)

คำตอบ
<!doctype html>

<html>
<head>
<meta charset="utf-8">
<link  href="exsimple4.css" rel="stylesheet" >

</head>

<body>
	
<div class="bg-box" id="bg-box" >
	<img src="bg.jpg" alt="img" />
	</div>
</body>
</html>

*{
	margin: 0;
	padding: 0;
}
img{
	width: 300px;
	height: 300px;

}


5. จงเขียนคำสั่งเพื่อกำหนด Animation ให้ DIV id=”blue-circle” มีลักษณะเป็นวงกลมสีฟ้าเคลื่อนที่จากซ้ายสุดของหน้าจอไปยังขวาสุดของหน้าจอและกลับมายังซ้ายสุดของหน้าจออีกครั้งและวนซํ้าแบบเดิมอย่างไม่มีที่สิ้นสุด

คำตอบ
<!doctype html>

<html>
<head>
<meta charset="utf-8">
<link  href="exsimple5.css" rel="stylesheet" >

</head>

<body>
	
<div id="blue-circle" >
	
	</div>
</body>
</html>

/*https://www.softmelt.com/article.php?id=452 อ้างอิง*/
 div{
    width: 140px; /* ความกว้าง */
    height: 140px; /* ความสูง */
    background: blue; /* สี */
    -moz-border-radius: 70px;
    -webkit-border-radius: 70px;
    border-radius: 70px;
	 position: absolute;
     animation-name: move;
     animation-duration: 6s;
     animation-timing-function: linear;
     animation-iteration-count: infinite;
     animation-direction: alternate;
	 
	
} 


  @keyframes move {
                0% {
                    
                    left: 0px;
                }
                50% {
                    
                    left: 500px;
                }
                100% {
                    

                    left: 1224px;
                }
                

                


            }
	    
	    
6. จงเขียนคำสั่งเพื่อกำหนด style ให้กับ Button id = “gradient-btn” ให้มีพื้นหลังแบบ gradient โดยเริ่มต้นจากสี#f6b144 ไปยังสี#e69220 แบบ linear-gradient ที่ direction 90 องศา

คำตอบ 

<!doctype html>

<html>
<head>
<meta charset="utf-8">
<link  href="exsimple6.css" rel="stylesheet" >

</head>

<body>
	
<button class="gradient-btn"></button>
</body>
</html>

*{
	margin: 0;
	padding: 0;
}

/*W3school อ้างอิง*/

button{
  
   
    background: -webkit-linear-gradient(#f6b144, #e69220); /* For Safari 5.1 to 6.0 */
    background: -o-linear-gradient(#f6b144, #e69220); /* For Opera 11.1 to 12.0 */
    background: -moz-linear-gradient(#f6b144, #e69220); /* For Firefox 3.6 to 15 */
    background: linear-gradient(#f6b144, #e69220); /* Standard syntax (must be last) */
	border: none;
    padding: 15px 32px;
    display: inline-block;
    margin: 100px 200px;
	height: 100vh;
	width: 100vh;
   
} 

7. จงเขียนคำสั่งเพื่อกำหนด style ให้กับ Button id = “fade-btn” โดยเมื่อเริ่มต้นให้ Button มีพื้นหลังสีแดงและเมื่อนํา Cursor ไปชี้(hover) จะค่อยๆ fade สีพื้นหลังเปลี่ยนเป็นสีเขียว

คำตอบ
<!doctype html>

<html>
<head>
<meta charset="utf-8">
<link  href="exsimple7.css" rel="stylesheet" >

</head>

<body>
	
<button class="button" id="fade-btn"  >Hover </button> 
	
</body>
</html>

*{
	margin: 0;
	padding: 0;
}

/*W3school อ้างอิง*/

button{
  
  display: inline-block;
  border-radius: 4px;
  background-color: red;
  border: none;
  color: #FFFFFF;
  text-align: center;
  font-size: 28px;
  padding: 20px;
  width: 200px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
    
	
} 
 
button:hover{background-color: green;}

button:active {
  background-color: green;
  
}

8. จงเขียนคำสั่งเพื่อกำหนด style ให้ DIV id = “red-box” ที่มีขนาดความกว้าง 150 x 150 px เมื่อนํา Cursor ไปชี้(hover) ขนาดความกว้างและสูงจะเพิ่มเป็น 2 เท่า

คำตอบ
<!doctype html>

<html>
<head>
<meta charset="utf-8">
<link  href="exsimple8.css" rel="stylesheet" >

</head>

<body>
	
<div id="red-box"></div> 
	
</body>
</html>

*{
	margin: 0;
	padding: 0;
}

/*W3school อ้างอิง*/

div{
  
  display: inline-block;
  border-radius: 4px;
  background-color: red;
  border: none;
  padding: 20px;
  width: 150px;
  height: 150px;
  transition: all 0.5s;
  cursor: pointer;
  margin: 5px;
  position: absolute;
  top: 50%;
  left: 50%;
  margin-top: -100px;
  margin-left: -100px;
    
	
} 
 
div:hover{width: 300px; height: 300px;}

div:active {
  width: 300px; height: 300px;
  
}

  
9. จงเขียนคำสั่งเพื่อจัด Layout ของกล่องสีเขียวแดงและน้ำเงินให้ได้ผลลัพธ์ดังรูปภาพตัวอย่าง

คำตอบ
<!doctype html>

<html>
<head>
<meta charset="utf-8">
<link  href="exsimple9.css" rel="stylesheet" >

</head>

<body>
	
<div class="GR" id="green-box"></div>
<div class="R" id="red-box"></div> 
<div class="B" id="blue-box"></div> 


	
</body>
</html>




.GR{
  
  width: 250px;
  height: 150px;
  background-color: green;
  border: 1px solid black;
    
	
} 
 
.R{
	
  width: 250px;
  height: 150px;
  background-color:red;
  margin-left: 250px;
}

.B{
	
  width: 250px;
  height: 150px;
  background-color:blue;
  margin-left: 500px;
}


10. หากกำหนดให้DIV id = “parent” มีขนาดตัวอักษร 20px และภายใต้ DIV id = “parent” มี DIV id =“child” ควรกำหนดขนาดตัวอักษรใน DIV id = “child” อย่างไรให้สัมพันธ์กับ DIV id = “parent” 

คำตอบ
<!doctype html>
<html>
<head>
	<link rel="stylesheet" href="exsimple10.css" >
	</head>	
<body>

<h1 id="parent">Parent and Child</h1>
<p id="child"></p>

<script>
document.getElementById("child").innerHTML = document.getElementById("parent").innerHTML;
</script>

</body>
</html>


JS
1.หากต้องการเข้าถึงหรือค้นหา DIV element ที่มี id = “mylist” สามารถเรียกใช้ผ่าน document method ใดได้บ้าง
<ไม่เข้าใจโจทย์ทำได้เท่านี้ สามารถส่งโจทย์มาใหม่ได้นะคะ>
คำตอบ
<!DOCTYPE html>
<html>
<body>
    <input type="text" id="mylist" value="">  
    <button onclick="myFunction()">Try it</button>
    
    <p id="demo"></p>
    
    <script>
       var num = [60, 70, 80, 90];

       function checkAdult(num) {
       return num >= 70;
                       }

       function myFunction() {
        document.getElementById("demo").innerHTML =num.find(checkAdult);
                           }

        
    </script>
 
</body>
</html>

2.จงเขียน style โดยใช้Javascript ให้DIV ที่มีid = “box” ให้มีกรอบสีเขียว พื้นหลังสีแดง มีค่า alpha ที่ 0.7 มีความกว้าง 100px และความสูง 100px

คำตอบ
<!DOCTYPE html>
<html>
    <body>
        
        <p id="p2"></p>

     <script>
      
      document.getElementById("p2").style.backgroundColor = "rgba(255,0,0,0.7)";
      document.getElementById("p2").style.width="100px";
      document.getElementById("p2").style.height="100px";
      document.getElementById("p2").style.border="medium solid green";

      </script>
    </body>
</html>

3.จงเขียนชุดคำสั่งเพื่อดึงข้อมูลที่ถูกกรอกลงในช่อง input ที่มีtype = text

คำตอบ
<!DOCTYPE html>
<html>
<body>

Field1: <input type="text" id="field1" value=""><br><br>

<button onclick="myFunction()">Copy Text</button>

<p id="demo"></p>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = document.getElementById("field1").value;
}
</script>

</body>
</html>

4.จงเขียนชุดคำสั่งเพื่อดึงข้อมูลที่ถูกเลือกในช่อง Input ที่มีtype = checkbox และ type = radio

คำตอบ
5. จงเขียนชุดคำสั่งเพื่อดึงข้อมูลที่ถูกเลือกใน select input

คำตอบ
<!DOCTYPE html>
<html>
<body>

    <form >
        <label for="cars">Choose a car:</label>
        <select name="cars" id="cars">
          <option value="toyota">toyota</option>
          <option value="honda">honda</option>
          <option value="isuzu">isuzu</option>
          <option value="MG">MG</option>
        </select>
        <br><br>
        
      </form>

<button onclick="myFunction()">Try Me</button>

<p id="demo"></p>

<script>
function myFunction() {
  document.getElementById("demo").innerHTML = document.getElementById("cars").value;
}
</script>

</body>
</html>

6. จงเขียน class โดยมี property price, amount และ discount และมีmethod ใน class ประกอบด้วย setPrice() เพื่อส่งค่า ให้price, setAmount() เพื่อส่งค่า ให้amount และ setDiscount() เพื่อส่งค่าให้
discount และ method summary() เพื่อ return ค่า (amount * price) - discount

คำตอบ
7.จงเขียนฟังก์ชันหรือชุดคำสั่งที่จะให้แสดงข้อความ “I Love You” ใน DIV element ที่มีid =“love-message” โดยข้อความจะแสดงเมื่อเวลาผ่านไปแล้ว 8 วินาที
ตัวอย่าง ผลลัพธ์
<div id=”love-message”>
I Love You
</div>

คำตอบ

10.จงเขียนฟังก์ชั่นหรือชุดคำสั่งเพื่อสลับตำแหน่งตัวอักษร (reverse) ของประโยค “I Love Javascript” เป็น “tpircsavaJ evoL I”

คำตอบ
<!DOCTYPE html>
<html>
<body>
<script>
 
 let site = "I Love Javascripts";
 let reversed = "";

  // Reverse string
  for (let i = site.length - 1; i >= 0; i--) {
    reversed += site[i];
}

console.log("Original: " + site);
console.log("Reversed: " + reversed);

</script>

</body>
</html>
