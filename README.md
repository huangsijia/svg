<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no">
<title>箭头酷跑</title>
</head>

<body>
  <!-- bging="0;left.end",bging="right.end" -->
  <svg width="100%" height="100%" viewBox="0 0 350 350">
    <path d="M 280 10,280 65,60 65,60 290,100 290" style="fill:none;stroke:#607d8b;stroke-width:1" />
    <path id="num" d="M 300 10,300 50,20 50,20 300,100 300" style="fill:none;stroke:#ff9800;stroke-width:2" />
    <path d="M 350 10,350 80,100 80,100 200,300 200" style="fill:none;stroke:green;stroke-width:2" />

    <path id="triangle" d="m 0 0 L 10 10 L 10 -10 Z" x="300" y="10" style="fill:red;stroke-width:1" />

    <animateMotion id="down" begin="0;up.end" xlink:href="#triangle" dur="15s" rotate="auto-reverse" repeatCount="indefinite">
      <mpath xlink:href="#num" />
    </animateMotion>
    
    <image xlink:href="a.png" x="100" y="280" width="30%"/>
  </svg>
</body>

</html>
