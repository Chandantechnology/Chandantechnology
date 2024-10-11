<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="
    width=device-width,initial-scale=1.0">
    <meta http-equiv="X-UA-compatible"
    content="ie=edge">
    <title>solar system</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body><div class="container">
  <div class="son"></div>
  <div class="earth">
  <div class="moon"></div></div></div>
   
  </body>
</html> 
body{
  margin: 0;
  height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  background-color: black;
}
.container
{
  font-size: 10 px;
  width:40em;
  height: 40em;
  position: relative;
  
}
.son{
  position: absolute;
  top: 15em;
  left: 15em;
  width: 10em;
  height: 10em;
  border-radius: 50%;
  background-color: blue;
  box-shadow: 00 3em yellow;
}
.earth,.moon{
  position: absolute;
  border-style:relative;
  border-color: white transparent;
  border-width: 0.10em 0.1em 00;
  border-radius: 50%;
  
}
.earth{
  top: 2em;
  left: 2em;
  width: 15em;
  height: 15em;
  animation:orbit 36.5em linear infinite;
  
  
}
.moon{
  top: 0;
  right: 0;
  width: 4em;
  height: 4em;
  animation: orbit 2.7s linear infinite;
}
  .earth::before,
  .moon::before{
    content: "";
    position:absolute;
    border-radius:50%;
}
.earth::before{
  top:2.8em;
  right:2.8em;
  width:1.2em;
  height:1.2em;
  background-color: silver;
  
}
@keyframes orbit{
  to{
    transform: rotate(360deg);
  }
}
}
}


<!---
Chandantechnology/Chandantechnology is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
