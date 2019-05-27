<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
  font-size: 17px;
}

#myVideo {
  position: absolute;
  right: 0;
  bottom: 0;
  min-width: 100%; 
  min-height: 100%;
    filter:brightness(25%);
    overflow: hidden;
  z-index: -1;
 
    object-fit: cover;
  

  
}

.content {
  position: fixed;
  bottom: 0;
  background: rgba(0, 0, 0, 0.5);
  color: #f1f1f1;
  width: 100%;
  padding: 20px;

}

#myBtn {
  width: 200px;
  font-size: 18px;
  padding: 10px;
  border: none;
  background: #000;
  color: #fff;
  cursor: pointer;
}

#myBtn:hover {
  background: #ddd;
  color: black;
}
</style>
</head>
<body>

<video autoplay muted loop id="myVideo">
  <source src="11.mp4" type="video/mp4">
  Your browser does not support HTML5 video.
</video>

<div class="content">
  <h1>John Sioras</h1>
  <p>Software developer with 15+ years of experience in Energy and Industrial Automation</p>
<script>
function sendEmail() 
{
    window.location = "mailto:jsiorass@gmail.com";
}
</script>
<div style="  width: 200px;
  font-size: 18px;
  padding: 10px;
  border: none;
  background: #000;
  color: #fff;
  cursor: pointer;" onclick="sendEmail();">Send e-mail</div>
  
  
</div>



</body>
</html>
