<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>36 Degree Time Clock</title>

<style>
body{
    margin:0;
    background:#111;
    color:white;
    font-family:Arial,sans-serif;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    text-align:center;
}

.clock{
    width:320px;
    height:320px;
    border:8px solid #00ffcc;
    border-radius:50%;
    position:relative;
    margin:auto;
    box-shadow:0 0 25px #00ffcc;
}

.center{
    width:12px;
    height:12px;
    background:white;
    border-radius:50%;
    position:absolute;
    top:50%;
    left:50%;
    transform:translate(-50%,-50%);
}

.hand{
    position:absolute;
    left:50%;
    bottom:50%;
    transform-origin:bottom center;
}

.hour{
    width:6px;
    height:80px;
    background:#00ffcc;
}

.minute{
    width:4px;
    height:110px;
    background:#ffffff;
}

.second{
    width:2px;
    height:130px;
    background:red;
}

.time{
    margin-top:25px;
    font-size:34px;
    font-weight:bold;
}

.degree{
    margin-top:10px;
    font-size:22px;
    color:#00ffcc;
}
</style>
</head>

<body>

<div class="container">

<div class="clock">
    <div class="hand hour" id="hour"></div>
    <div class="hand minute" id="minute"></div>
    <div class="hand second" id="second"></div>
    <div class="center"></div>
</div>

<div class="time" id="display"></div>
<div class="degree" id="degree"></div>

</div>

<script>

function updateClock(){

    let now = new Date();

    let midnight =
        new Date(
            now.getFullYear(),
            now.getMonth(),
            now.getDate()
        );

    let elapsed =
        (now - midnight);

    let fraction =
        elapsed / 86400000;

    let total =
        fraction * (36*36*36*36);

    let h = Math.floor(total/(36*36*36));
    total %= (36*36*36);

    let m = Math.floor(total/(36*36));
    total %= (36*36);

    let s = Math.floor(total/36);
    let ms = Math.floor(total%36);

    document.getElementById("display").innerHTML =
        String(h).padStart(2,'0') + ":" +
        String(m).padStart(2,'0') + ":" +
        String(s).padStart(2,'0') + ":" +
        String(ms).padStart(2,'0');

    let hourDeg = h * 10 + (m/36)*10;
    let minuteDeg = m * 10;
    let secondDeg = s * 10;

    document.getElementById("degree").innerHTML =
        "Degree : " + hourDeg.toFixed(2) + "°";

    document.getElementById("hour").style.transform =
        `translateX(-50%) rotate(${hourDeg}deg)`;

    document.getElementById("minute").style.transform =
        `translateX(-50%) rotate(${minuteDeg}deg)`;

    document.getElementById("second").style.transform =
        `translateX(-50%) rotate(${secondDeg}deg)`;
}

setInterval(updateClock,50);
updateClock();

</script>

</body>
</html>
