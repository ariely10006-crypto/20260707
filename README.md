<!DOCTYPE html>
<html lang="zh-TW">
<head>
<meta charset="UTF-8">
<title>Dora Soccer Drone</title>

<style>

body{
    margin:0;
    font-family:"Microsoft JhengHei";
    background:#8fd3ff;
}

header{
    background:#0099ff;
    color:white;
    text-align:center;
    padding:50px;
}

.hero{
    text-align:center;
    padding:60px;
}

.hero h1{
    font-size:50px;
}

.hero p{
    font-size:22px;
}

button{
    padding:15px 35px;
    border:none;
    border-radius:30px;
    background:#ff5050;
    color:white;
    font-size:20px;
    cursor:pointer;
}

.features{
    display:flex;
    justify-content:center;
    gap:30px;
    flex-wrap:wrap;
    padding:50px;
}

.card{
    background:white;
    width:250px;
    padding:20px;
    border-radius:20px;
    box-shadow:0 5px 15px rgba(0,0,0,.2);
    text-align:center;
}

footer{
    background:#0099ff;
    color:white;
    text-align:center;
    padding:20px;
}

.drone{
    font-size:80px;
    animation:fly 3s infinite ease-in-out;
}

@keyframes fly{
    0%{transform:translateY(0);}
    50%{transform:translateY(-20px);}
    100%{transform:translateY(0);}
}

</style>

</head>

<body>

<header>
<h1>⚽ Dora Soccer Drone 🚁</h1>
<p>來自未來的足球無人機</p>
</header>

<section class="hero">

<div class="drone">🚁⚽</div>

<h1>飛向夢想</h1>

<p>AI 足球追蹤｜智慧射門分析｜自動飛行</p>

<button>開始體驗</button>

</section>

<section class="features">

<div class="card">
<h2>🚁 自動追蹤</h2>
<p>即時鎖定足球位置</p>
</div>

<div class="card">
<h2>⚽ AI分析</h2>
<p>紀錄每次射門數據</p>
</div>

<div class="card">
<h2>📹 4K錄影</h2>
<p>高畫質比賽拍攝</p>
</div>

<div class="card">
<h2>🎮 遙控模式</h2>
<p>手機一鍵控制</p>
</div>

</section>

<footer>
©2026 Dora Soccer Drone
</footer>

</body>
</html>
