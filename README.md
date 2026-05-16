<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>Ngô Lê Phương Nhi - ACB</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
font-family:'Be Vietnam Pro',sans-serif;
background:#f4f7fc;
color:#0b1d4d;
}

.container{
max-width:1200px;
margin:auto;
padding:20px;
}

.hero{
background:white;
border-radius:35px;
padding:40px;
display:flex;
gap:40px;
align-items:center;
box-shadow:0 10px 40px rgba(0,0,0,0.08);
margin-top:30px;
flex-wrap:wrap;
}

.avatar{
width:320px;
height:320px;
border-radius:50%;
object-fit:cover;
border:10px solid #d7e7ff;
box-shadow:0 10px 30px rgba(0,87,194,0.2);
}

.info{
flex:1;
min-width:300px;
}

.badge{
display:inline-block;
padding:10px 18px;
background:#e9f1ff;
border-radius:30px;
font-weight:600;
color:#0057c2;
margin-bottom:20px;
}

.name{
font-size:56px;
font-weight:800;
line-height:1.1;
}

.role{
margin-top:15px;
display:inline-block;
padding:12px 20px;
background:#edf3ff;
color:#0057c2;
border-radius:20px;
font-weight:600;
}

.desc{
margin-top:25px;
font-size:20px;
line-height:1.8;
color:#4f5b7a;
}

.contact{
display:flex;
gap:20px;
margin-top:35px;
flex-wrap:wrap;
}

.contact-btn{
background:white;
border-radius:22px;
padding:18px 25px;
display:flex;
align-items:center;
gap:15px;
text-decoration:none;
color:#0b1d4d;
box-shadow:0 5px 20px rgba(0,0,0,0.06);
font-weight:600;
}

.zalo{
background:#0057c2;
color:white;
}

.code-box{
margin-top:35px;
background:linear-gradient(135deg,#0057c2,#003f99);
border-radius:30px;
padding:35px;
display:flex;
justify-content:space-between;
align-items:center;
color:white;
flex-wrap:wrap;
gap:20px;
}

.code-title{
font-size:20px;
opacity:0.9;
}

.code{
font-size:70px;
font-weight:800;
margin-top:10px;
}

.copy-btn{
background:rgba(255,255,255,0.15);
border:none;
padding:20px 30px;
border-radius:22px;
color:white;
font-size:20px;
cursor:pointer;
font-weight:600;
}

.features{
margin-top:35px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.feature{
background:white;
padding:30px;
border-radius:25px;
text-align:center;
box-shadow:0 5px 20px rgba(0,0,0,0.05);
}

.feature h3{
margin-top:15px;
font-size:22px;
}

.feature p{
margin-top:10px;
color:#667;
line-height:1.6;
}

.section-title{
margin-top:60px;
font-size:40px;
font-weight:800;
}

.cards{
margin-top:30px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
gap:30px;
}

.card{
background:white;
border-radius:30px;
padding:25px;
box-shadow:0 10px 30px rgba(0,0,0,0.06);
transition:0.3s;
}

.card:hover{
transform:translateY(-8px);
}

.card img{
width:100%;
border-radius:20px;
}

.card h2{
margin-top:20px;
font-size:30px;
}

.card p{
margin-top:10px;
color:#5a6787;
line-height:1.7;
}

.card ul{
margin-top:20px;
padding-left:20px;
line-height:2;
color:#223;
}

.apply-btn{
margin-top:25px;
display:block;
text-align:center;
background:#0057c2;
padding:16px;
border-radius:18px;
text-decoration:none;
color:white;
font-weight:700;
font-size:18px;
}

.footer{
margin-top:80px;
padding:40px;
text-align:center;
color:#678;
}

@media(max-width:768px){

.name{
font-size:42px;
}

.avatar{
width:240px;
height:240px;
margin:auto;
}

.hero{
padding:25px;
}

.code{
font-size:52px;
}

.section-title{
font-size:32px;
}

}

</style>
</head>

<body>

<div class="container">

<div class="hero">

<img class="avatar"
src="https://i.imgur.com/FWb4Q6x.jpeg">

<div class="info">

<div class="badge">
Chuyên viên tư vấn tài chính
</div>

<div class="name">
Ngô Lê Phương Nhi
</div>

<div class="role">
Nhân viên dịch vụ khách hàng cá nhân ACB
</div>

<div class="desc">
Đồng hành cùng khách hàng trên hành trình tài chính cá nhân —
tư vấn tận tâm, giải pháp phù hợp, trải nghiệm xứng tầm.
</div>

<div class="contact">

<a class="contact-btn"
href="tel:0902883935">
📞 0902 883 935
</a>

<a class="contact-btn zalo"
href="https://zalo.me/0902883935">
💬 Nhắn Zalo ngay
</a>

</div>

</div>

</div>

<div class="code-box">

<div>
<div class="code-title">
MÃ GIỚI THIỆU
</div>

<div class="code">
774021
</div>
</div>

<button class="copy-btn"
onclick="copyCode()">
📋 Sao chép mã
</button>

</div>

<div class="features">

<div class="feature">
<h3>🔒 An toàn bảo mật</h3>
<p>Chuẩn ngân hàng số hiện đại</p>
</div>

<div class="feature">
<h3>⚡ Duyệt nhanh</h3>
<p>Hỗ trợ hồ sơ nhanh chóng</p>
</div>

<div class="feature">
<h3>🎁 Ưu đãi hấp dẫn</h3>
<p>Nhiều chương trình hoàn tiền</p>
</div>

<div class="feature">
<h3>💎 Hỗ trợ tận tâm</h3>
<p>Tư vấn trực tiếp 24/7</p>
</div>

</div>

<div class="section-title">
Thẻ tín dụng nổi bật
</div>

<div class="cards">

<div class="card">

<img src="https://i.imgur.com/oz2kM6G.jpeg">

<h2>ACB Visa Gold</h2>

<p>
Đáp ứng nhu cầu tài chính ngắn hạn,
nhiều ưu đãi hoàn tiền và trả góp.
</p>

<ul>
<li>Hạn mức từ 5 triệu</li>
<li>Miễn lãi đến 45 ngày</li>
<li>Ngày sao kê 26 hàng tháng</li>
<li>Phí thường niên 499.000 VND</li>
</ul>

<a class="apply-btn"
href="https://zalo.me/0902883935">
Tìm hiểu & Đăng ký
</a>

</div>

<div class="card">

<img src="https://i.imgur.com/q2aF3y7.jpeg">

<h2>ACB Privilege Visa Signature</h2>

<p>
Dòng thẻ cao cấp cho khách hàng ưu tiên,
đặc quyền sân bay và rewards.
</p>

<ul>
<li>Hạn mức từ 100 triệu</li>
<li>Miễn lãi đến 55 ngày</li>
<li>Miễn phí thường niên</li>
<li>Ưu đãi Dragon Pass</li>
</ul>

<a class="apply-btn"
href="https://zalo.me/0902883935">
Tìm hiểu & Đăng ký
</a>

</div>

<div class="card">

<img src="https://i.imgur.com/YZQp9Zr.jpeg">

<h2>ACB JCB Gold</h2>

<p>
Thanh toán linh hoạt,
ưu đãi mua sắm và hoàn phí hấp dẫn.
</p>

<ul>
<li>Miễn lãi đến 45 ngày</li>
<li>Trả góp linh hoạt</li>
<li>Hoàn phí thường niên</li>
<li>Ưu đãi đối tác mỗi ngày</li>
</ul>

<a class="apply-btn"
href="https://zalo.me/0902883935">
Tìm hiểu & Đăng ký
</a>

</div>

</div>

<div class="footer">
© 2026 ACB — Landing page tư vấn tài chính cá nhân
</div>

</div>

<script>

function copyCode(){

navigator.clipboard.writeText("774021");

alert("Đã sao chép mã giới thiệu!");

}

</script>

</body>
</html>
