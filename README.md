# suong-mai-coffee
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sương Mai Coffee — Từ Cầu Đất, vào từng tách cà phê</title>
<style>
:root{
  --coffee:#3b2a20; --coffee2:#654638; --cream:#f5efe5;
  --paper:#fbf8f2; --green:#596b52; --line:#ded5c8;
  --text:#29241f; --muted:#746b62;
}
*{box-sizing:border-box} html{scroll-behavior:smooth}
body{margin:0;font-family:Inter,Arial,sans-serif;color:var(--text);background:var(--paper);line-height:1.6}
nav{position:fixed;top:0;left:0;right:0;z-index:10;display:flex;justify-content:space-between;align-items:center;padding:18px 6%;background:rgba(251,248,242,.92);backdrop-filter:blur(12px);border-bottom:1px solid rgba(222,213,200,.7)}
.logo{font-family:Georgia,serif;font-size:25px;font-weight:700;color:var(--coffee)}
nav a{color:var(--text);text-decoration:none;margin-left:26px;font-size:14px}
nav a:hover{color:var(--green)}
.hero{min-height:760px;padding:170px 7% 90px;display:grid;grid-template-columns:1.05fr .95fr;gap:70px;align-items:center;background:linear-gradient(135deg,#f5efe5 0%,#ebe3d5 100%)}
.kicker{text-transform:uppercase;letter-spacing:3px;color:var(--green);font-size:12px;font-weight:700}
h1{font-family:Georgia,serif;font-size:clamp(48px,7vw,88px);line-height:.98;margin:18px 0 28px;color:var(--coffee);font-weight:500}
.hero p{max-width:570px;font-size:18px;color:var(--muted)}
.btn{display:inline-block;margin-top:24px;padding:13px 22px;border-radius:30px;text-decoration:none;font-weight:700;font-size:14px}
.btn-dark{background:var(--coffee);color:white}.btn-light{border:1px solid var(--coffee);color:var(--coffee);margin-left:8px}
.hero-card{height:510px;border-radius:180px 180px 24px 24px;background:
radial-gradient(circle at 50% 45%,rgba(255,255,255,.25),transparent 26%),
linear-gradient(145deg,#755645,#2f211a);position:relative;overflow:hidden;box-shadow:0 30px 70px rgba(59,42,32,.18)}
.hero-card:before{content:"";position:absolute;width:300px;height:300px;border-radius:50%;border:1px solid rgba(255,255,255,.25);top:90px;left:50%;transform:translateX(-50%)}
.hero-card:after{content:"SƯƠNG MAI";position:absolute;bottom:70px;left:50%;transform:translateX(-50%);color:#f5efe5;font:28px Georgia,serif;letter-spacing:5px}
section{padding:100px 7%}.intro{display:grid;grid-template-columns:.7fr 1.3fr;gap:90px}
.eyebrow{font-size:12px;text-transform:uppercase;letter-spacing:2px;color:var(--green);font-weight:700}
h2{font:500 clamp(36px,5vw,60px)/1.05 Georgia,serif;color:var(--coffee);margin:12px 0 24px}
.large{font:25px/1.5 Georgia,serif;color:var(--coffee)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:45px}
.card{background:white;border:1px solid var(--line);border-radius:22px;padding:28px}
.card .num{font:38px Georgia,serif;color:var(--green)}
.card h3{font:22px Georgia,serif;margin:10px 0;color:var(--coffee)}
.card p{color:var(--muted);font-size:14px}
.story{background:var(--coffee);color:#f7f0e6;display:grid;grid-template-columns:1fr 1fr;gap:70px;align-items:center}
.story h2{color:#f7f0e6}.story p{color:#ded3c6}.timeline{border-left:1px solid #9b8878;padding-left:30px}
.timeline div{margin:0 0 30px}.timeline b{color:#d9c7b5;font-size:28px;font-family:Georgia,serif}
.menu-head{display:flex;justify-content:space-between;align-items:end}
.menu{display:grid;grid-template-columns:repeat(2,1fr);gap:0;border-top:1px solid var(--line);margin-top:35px}
.item{padding:24px 8px;border-bottom:1px solid var(--line);display:flex;justify-content:space-between;gap:20px}
.item h3{margin:0;font:20px Georgia,serif;color:var(--coffee)}.item small{color:var(--muted)}
.price{font-weight:800;color:var(--coffee);white-space:nowrap}
.cup{background:var(--cream)}
.store-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:40px}
.store{min-height:250px;background:#fff;border-radius:22px;padding:25px;border:1px solid var(--line)}
.store h3{font:25px Georgia,serif;color:var(--coffee)}
.tag{display:inline-block;padding:5px 10px;border-radius:20px;background:#e9eee6;color:var(--green);font-size:11px;font-weight:700}
.cta{margin:30px 7% 100px;padding:70px 8%;background:var(--green);border-radius:35px;color:white;text-align:center}
.cta h2{color:white}.cta p{max-width:650px;margin:auto;color:#edf0e9}
footer{background:#251b16;color:#d9cec2;padding:55px 7%;display:flex;justify-content:space-between;gap:30px}
footer strong{font:24px Georgia,serif;color:#fff} footer a{color:#d9cec2;text-decoration:none;margin-left:18px}
@media(max-width:850px){
 nav a{display:none}.hero,.intro,.story{grid-template-columns:1fr}.hero{padding-top:130px}.hero-card{height:400px}
 .grid,.store-grid{grid-template-columns:1fr}.menu{grid-template-columns:1fr}.menu-head{display:block}
}
</style>
</head>
<body>
<nav>
  <div class="logo">Sương Mai Coffee</div>
  <div>
    <a href="#story">Câu chuyện</a><a href="#coffee">Cà phê</a><a href="#menu">Menu</a><a href="#stores">Cửa hàng</a>
  </div>
</nav>

<header class="hero">
  <div>
    <div class="kicker">Da Lat · Cau Dat · Since 2018</div>
    <h1>Từ Cầu Đất,<br>vào từng tách cà phê.</h1>
    <p>Sương Mai bắt đầu từ một quầy rang nhỏ tại Đà Lạt năm 2018. Chúng mình chọn Arabica Cầu Đất, rang theo từng mẻ nhỏ và giữ cách kể chuyện giản dị về một ly cà phê được làm thật.</p>
    <a class="btn btn-dark" href="#coffee">Khám phá Sương Mai</a>
    <a class="btn btn-light" href="#stores">Tìm cửa hàng</a>
  </div>
  <div class="hero-card" aria-label="Hình minh họa ly cà phê"></div>
</header>

<section id="story" class="intro">
  <div><div class="eyebrow">Our story</div><h2>Một câu chuyện bắt đầu từ Đà Lạt.</h2></div>
  <div>
    <p class="large">Sương Mai được xây dựng từ câu chuyện về cà phê Cầu Đất, những người trồng cà phê và những mẻ rang nhỏ tại Đà Lạt.</p>
    <p>Thay vì nói về cà phê bằng những thuật ngữ khó hiểu, Sương Mai muốn giúp bạn hiểu nguồn gốc, cách rang và cách chọn một món phù hợp với gu của mình.</p>
    <div class="grid">
      <div class="card"><div class="num">2018</div><h3>Bắt đầu tại Đà Lạt</h3><p>Từ một quầy rang nhỏ, Sương Mai phát triển câu chuyện cà phê của mình.</p></div>
      <div class="card"><div class="num">12</div><h3>Hộ trồng Arabica</h3><p>Nguồn nguyên liệu được gắn với vùng Cầu Đất và người trồng.</p></div>
      <div class="card"><div class="num">6</div><h3>Cửa hàng</h3><p>Hiện diện tại Đà Lạt và TP.HCM để khách dễ tìm và trải nghiệm.</p></div>
    </div>
  </div>
</section>

<section class="story" id="coffee">
  <div>
    <div class="eyebrow">From bean to cup</div>
    <h2>Nguồn gốc thật.<br>Cách làm thật.</h2>
    <p>Arabica Cầu Đất được rang theo từng mẻ nhỏ. Mức rang vừa được dùng làm chuẩn chung cho pha phin và pha máy, hướng tới trải nghiệm nhất quán.</p>
  </div>
  <div class="timeline">
    <div><b>01 · Cầu Đất</b><br>Hạt Arabica từ 12 hộ trồng.</div>
    <div><b>02 · Rang</b><br>Rang theo từng mẻ nhỏ tại Đà Lạt.</div>
    <div><b>03 · Pha</b><br>Phin truyền thống hoặc pha máy.</div>
    <div><b>04 · Thưởng thức</b><br>Một ly cà phê phù hợp với khoảnh khắc của bạn.</div>
  </div>
</section>

<section id="menu">
  <div class="menu-head">
    <div><div class="eyebrow">Menu</div><h2>Uống gì hôm nay?</h2></div>
    <p>Những lựa chọn dễ hiểu, từ cà phê phin đến pha máy.</p>
  </div>
  <div class="menu">
    <div class="item"><div><h3>Phin sữa đá</h3><small>Món bán chạy · pha phin truyền thống</small></div><div class="price">45.000đ</div></div>
    <div class="item"><div><h3>Cà phê đen đá</h3><small>Vị cà phê truyền thống</small></div><div class="price">40.000đ</div></div>
    <div class="item"><div><h3>Americano</h3><small>Cà phê pha máy</small></div><div class="price">50.000đ</div></div>
    <div class="item"><div><h3>Latte / Cappuccino</h3><small>Mượt mà, pha máy</small></div><div class="price">60.000đ</div></div>
    <div class="item"><div><h3>Cold Brew</h3><small>Ủ lạnh 12 giờ</small></div><div class="price">65.000đ</div></div>
    <div class="item"><div><h3>Trà đào cam sả</h3><small>Lựa chọn không cà phê</small></div><div class="price">55.000đ</div></div>
  </div>
</section>

<section class="cup">
  <div class="intro">
    <div><div class="eyebrow">A small ritual</div><h2>Hai phút chờ.<br>Một khoảnh khắc chậm lại.</h2></div>
    <div><p class="large">Một ly phin sữa đá không phải là thứ cần uống thật nhanh.</p><p>Khoảng thời gian chờ pha phin là một phần của trải nghiệm Sương Mai — từ tiếng nước, mùi cà phê đến khoảnh khắc giọt cuối cùng rơi xuống.</p></div>
  </div>
</section>

<section id="stores">
  <div class="eyebrow">Find us</div><h2>Ghé Sương Mai gần bạn.</h2>
  <p>Hai thành phố, một câu chuyện cà phê.</p>
  <div class="store-grid">
    <div class="store"><span class="tag">ĐÀ LẠT</span><h3>Cửa hàng Đà Lạt 01</h3><p>Không gian cà phê mang câu chuyện Cầu Đất và Đà Lạt.</p><a class="btn btn-light" href="#">Chỉ đường →</a></div>
    <div class="store"><span class="tag">ĐÀ LẠT</span><h3>Cửa hàng Đà Lạt 02</h3><p>Một điểm dừng cho hành trình khám phá thành phố.</p><a class="btn btn-light" href="#">Chỉ đường →</a></div>
    <div class="store"><span class="tag">TP.HCM</span><h3>Cửa hàng TP.HCM</h3><p>Phù hợp cho ly cà phê quen thuộc giữa nhịp làm việc.</p><a class="btn btn-light" href="#">Chỉ đường →</a></div>
  </div>
</section>

<div class="cta">
  <div class="eyebrow" style="color:#d9e2d4">Sương Mai Coffee</div>
  <h2>Một ly cà phê. Một câu chuyện thật.</h2>
  <p>Khám phá cà phê Cầu Đất, tìm món hợp gu và ghé cửa hàng Sương Mai gần bạn.</p>
  <a class="btn" style="background:white;color:#3b2a20" href="#menu">Xem menu</a>
</div>

<footer>
  <div><strong>Sương Mai Coffee</strong><br><small>From Cau Dat to your cup.</small></div>
  <div><a href="#story">Câu chuyện</a><a href="#menu">Menu</a><a href="#stores">Cửa hàng</a></div>
</footer>
</body>
</html>
