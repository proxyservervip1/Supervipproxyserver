<!DOCTYPE html>
<html lang="en">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Free Fire Access</title>

<style>
body{
    margin:0;
    background:#0f0f0f;
    font-family:Arial;
    color:#fff;
}

/* TOP BAR */
.top{
    background:linear-gradient(90deg,#87c9e8,#5aa7d9);
    padding:18px;
    text-align:center;
    font-weight:bold;
    font-size:20px;
}

/* TITLE */
.title{
    text-align:center;
    margin:25px 0 20px;
    font-size:22px;
    letter-spacing:1px;
}

/* VIDEO */
.video-wrap{
    display:flex;
    justify-content:center;
    margin-bottom:30px;
}

.video-box{
    width:92%;
    max-width:360px;
    background:#000;
    border-radius:20px;
    overflow:hidden;
}

video{
    width:100%;
    display:block;
}

/* CARD */
.card-area{
    display:flex;
    justify-content:center;
    padding:0 18px 40px;
}

.card{
    width:100%;
    max-width:360px;
    background:#1a1a1a;
    border-radius:25px;
    padding:22px;
    position:relative;
}

/* GLOW BORDER */
.card:before{
    content:"";
    position:absolute;
    inset:-3px;
    border-radius:28px;
    background:linear-gradient(45deg, red, orange, yellow, green, cyan, blue, purple, red);
    z-index:-1;
    filter:blur(12px);
}

/* ROW */
.row{
    display:flex;
    gap:15px;
    align-items:center;
}

.icon{
    width:75px;
    border-radius:15px;
}

.content{
    text-align:left;
}

.badges{
    margin-bottom:5px;
}

.badge{
    padding:5px 12px;
    border-radius:20px;
    font-size:12px;
    margin-right:5px;
}

.new{
    background:#ff2b2b;
}

.premium{
    background:#7a2bff;
}

.name{
    font-size:18px;
    font-weight:bold;
}

.desc{
    font-size:13px;
    color:#bbb;
}

.stars{
    color:gold;
    margin-top:5px;
}

/* BUTTON */
.install{
    display:block;
    margin-top:20px;
    text-align:center;
    background:#16c95f;
    padding:16px;
    border-radius:35px;
    color:#fff;
    text-decoration:none;
    font-size:18px;
    font-weight:bold;
    transition:0.2s;
    box-shadow:0 8px 20px rgba(0,255,120,0.15);
}

.install:active{
    transform:scale(0.96);
    background:#12a94f;
}

/* FOOTER */
.footer{
    text-align:center;
    font-size:12px;
    color:#ff2b2b;
    padding-bottom:15px;
}
</style>
</head>

<body>

<div class="top">Garena Free Fire Team</div>

<div class="title">WATCH FULL VIDEO</div>

<div class="video-wrap">
    <div class="video-box">
        <video id="promoVideo" autoplay muted loop controls>
            <source src="video.mp4" type="video/mp4">
        </video>
    </div>
</div>

<div class="card-area">
    <div class="card">

        <div class="row">
            <img src="image.jpg" class="icon" alt="Proxy Server">

            <div class="content">
                <div class="badges">
                    <span class="badge new">NEW</span>
                    <span class="badge premium">PREMIUM</span>
                </div>

                <div class="name">SUPER VIP PROXY SERVER</div>
                <div class="desc">FREE FIRE PROXY SERVER UNLIMITED ACCESS</div>

                <div class="stars">★★★★★</div>
            </div>
        </div>

        <a href="https://aff.earnsiozone.in/click/u/87/o/14" class="install">⬇ Install</a>

    </div>
</div>

<div class="footer">Subscribe to Gamer Ayan</div>

<script>
document.addEventListener('click', function () {
    const video = document.getElementById('promoVideo');
    video.muted = false;
    video.play();
}, { once: true });
</script>

</body>
</html>
