# HTML5-canvas-all-code


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 canvas</title>
</head>
<body>
    
<!-- <canvas id="myCanvas" width="240px" height="297px" style="border: 2px solid red; background-repeat: no-repeat; background-size:cover;"></canvas> -->





<!-- <img src="Samiul.jpg" alt="samiul" width="200px" height="237px" id="img1"  /> -->




<canvas id="text" width="220px" height="150px" style= "border: 1px solid red;"></canvas>

<script>
 var c = document.getElementById("text");
 var ctx =c.getContext('2d');
ctx.shadowBlur = 10;
ctx.shadowcolor ="YELLOW";
ctx.shadowcolor ="red";
ctx.fillStyle = "BLUE";
ctx.shadowOffsetY = 20

ctx.fillRect(20,20,180,110)






//   var canvas = document.getElementById("myCanvas");
//   var ctx = canvas.getContext("2d");



//  ctx.fillStyle = 'green';
//   ctx.fillRect(0, 0, 200, 100);
  


// ctx.moveTo(0,0)
// ctx.lineTo(300,300)
// ctx.stroke()

// ctx.beginPath();
// ctx.arc(145,90,65,0,2*Math.PI);
// ctx.stroke();







// canvas gradient and text highlighting systm

// var grd = ctx.createLinearGradient(0,0,200,100);// element need for/






// var grd = ctx.createRadialGradient(80, 80, 10, 100, 140, 140)//6 elemenet need for createRadialGradient//
// grd.addColorStop(1, "green");
// grd.addColorStop(0, "red");



// ctx.fillStyle =grd;
// ctx.fillRect(70,48,150,80,2*Math.PI);



///Here we will show about font size


// ctx.font = '30px Comic Sans MS';
// ctx.fillStyle ="red";
// ctx.textAlign= 'center';
// ctx.fillText("Hello Guys", canvas.width/2, canvas.height/2);


//Here i will show about image setup on canvus

//  window.onload=function(){
// var canvas = document.getElementById('myCanvas');
// var ctx = canvas.getContext("2d");


// var img = document.getElementById('img1');
//  ctx.drawImage(img,0,0)

// }

/// color style and shadow system style







</script>
</body>
</html>
