<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EARTH360 CLOCK</title>

<style>
body{
    margin:0;
    background:#000;
    color:#fff;
    font-family:Arial, Helvetica, sans-serif;
    display:flex;
    justify-content:center;
    align-items:center;
    min-height:100vh;
    text-align:center;
}

.container{
    padding:20px;
}

.title{
    font-size:28px;
    letter-spacing:3px;
    margin-bottom:25px;
}

.dt{
    font-size:80px;
    font-weight:bold;
    margin-bottom:15px;
}

.rotation{
    font-size:20px;
    color:#bbbbbb;
    margin-bottom:25px;
}

.time24{
    font-size:32px;
    margin-bottom:10px;
}

.time12{
    font-size:28px;
    margin-bottom:20px;
}

.date{
    font-size:22px;
    margin-bottom:30px;
}

.tagline{
    font-size:14px;
    letter-spacing:4px;
    color:#aaaaaa;
}
</style>
</head>

<body>

<div class="container">

<div class="title">
EARTH360 CLOCK
</div>

<div class="dt" id="dt">
0.000 DT
</div>

<div class="rotation" id="rotation">
EARTH ROTATION: 0.000°
</div>

<div class="time24" id="time24">
00:00:00 UTC
</div>

<div class="time12" id="time12">
12:00:00 AM UTC
</div>

<div class="date" id="date">
01 JAN 2026
</div>

<div class="tagline">
ONE EARTH • ONE TIME
</div>

</div>

<script>

function updateClock(){

    const now = new Date();

    const utcSeconds =
        now.getUTCHours() * 3600 +
        now.getUTCMinutes() * 60 +
        now.getUTCSeconds() +
        (now.getUTCMilliseconds() / 1000);

    const dt = (utcSeconds / 86400) * 360;

    document.getElementById("dt").innerHTML =
        dt.toFixed(3) + " DT";

    document.getElementById("rotation").innerHTML =
        "EARTH ROTATION: " + dt.toFixed(3) + "°";

    const h24 = String(now.getUTCHours()).padStart(2,"0");
    const m24 = String(now.getUTCMinutes()).padStart(2,"0");
    const s24 = String(now.getUTCSeconds()).padStart(2,"0");

    document.getElementById("time24").innerHTML =
        h24 + ":" + m24 + ":" + s24 + " UTC";

    document.getElementById("time12").innerHTML =
        now.toLocaleTimeString("en-US",{
            hour12:true,
            timeZone:"UTC"
        }) + " UTC";

    document.getElementById("date").innerHTML =
        now.toLocaleDateString("en-GB",{
            day:"2-digit",
            month:"short",
            year:"numeric",
            timeZone:"UTC"
        }).toUpperCase();
}

updateClock();
setInterval(updateClock,100);

</script>

</body>
</html>
