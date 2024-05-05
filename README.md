<html>
  <head><h1>AP Literature Cards</h1></head>
  <body>
   <style>
.flip-card {
  background-color: transparent;
  width: 300 px;
  height: 300 px;
  perspective: 1000 px;
}
.flip-card-inner {
  position: relative;
  width: 100 %;
  height: 100 %;
  text-align: center;
  transition: transform 0.6 s;
  transform-style: preserve-3d;
  box-shadow: 0 4 px 8 px 0 rgba (0,0,0,0.2);
}
.flip-card:hover .flip-card-inner {
  transform: rotateY (180 deg);
}
.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100 %;
  height: 100 %;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}
.flip-card-front {
  background-color: #bbb;
  color: black;
}
.flip-card-back {
  background-color: #2980b9;
  color: white;
  transform: rotateY (180 deg);
}
</style>
<body>
<div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <p>Alliteration</p>
    <div class="flip-card-back">
      <p>repition of a consonant</p> 
    </div>
  </div>
</div>
  </body>
</html>
