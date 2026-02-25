
<!DOCTYPE html>
<html>
<head>
<title>माझी माहिती</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {margin:0;padding:0;box-sizing:border-box;}
body {
font-family:'Segoe UI',Arial,sans-serif;
background:linear-gradient(135deg,#667eea 0%,#764ba2 100%);
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
padding:20px;
}
.card {
background: rgba(255,255,255,0.95);
backdrop-filter: blur(10px);
border-radius:25px;
padding:40px 30px;
max-width:400px;
width:100%;
box-shadow:0 20px 40px rgba(0,0,0,0.1);
text-align:center;
transform:translateY(20px);
animation:slideUp 0.8s ease;
}
@keyframes slideUp {
from {opacity:0; transform:translateY(50px);}
to {opacity:1; transform:translateY(20px);}
}
.profile-pic {
width:100px;height:100px;
border-radius:50%;
background:linear-gradient(45deg,#ff6b6b,#feca57);
margin:0 auto 20px;
display:flex;
align-items:center;
justify-content:center;
font-size:40px;
color:white;
box-shadow:0 10px 30px rgba(0,0,0,0.2);
}
h1 {
color:#2c3e50;
font-size:28px;
font-weight:700;
margin-bottom:10px;
text-shadow:0 2px 4px rgba(0,0,0,0.1);
}
.subtitle {
color:#7f8c8d;
font-size:16px;
margin-bottom:30px;
}
.contacts {
display:flex;
flex-direction:column;
gap:15px;
}
.btn {
display:block;
padding:15px 25px;
background:linear-gradient(45deg,#11998e,#38ef7d);
color:white;
text-decoration:none;
border-radius:50px;
font-weight:600;
font-size:16px;
transition:all 0.3s ease;
box-shadow:0 8px 25px rgba(17,153,142,0.3);
position:relative;
overflow:hidden;
}
.btn:hover {
transform:translateY(-3px);
box-shadow:0 12px 35px rgba(17,153,142,0.4);
}
.btn:active {transform:translateY(-1px);}
.btn:before {
content:'';
position:absolute;
top:0;left:-100%;
width:100%;height:100%;
background:linear-gradient(90deg,transparent,rgba(255,255,255,0.3),transparent);
transition:0.5s;
}
.btn:hover:before {left:100%;}
.whatsapp {background:linear-gradient(45deg,#25D366,#128C7E);}
.instagram {background:linear-gradient(45deg,#E4405F,#F77737);}
.phone {background:linear-gradient(45deg,#FF6B6B,#FF8E8E);}
.footer {
margin-top:30px;
padding-top:20px;
border-top:2px solid #ecf0f1;
color:#95a5a6;
font-size:14px;
}
</style>
</head>
<body>
<div class="card">
<div class="profile-pic">👤</div>
<h1>[तुमचे नाव]</h1>
<div class="subtitle">Connect with me!</div>
<div class="contacts">
<a href="tel:+9198XXXXXXXXX" class="btn phone">📞 Call [+91 98XXXXXXXX]</a>
<a href="https://wa.me/+9198XXXXXXXXX" class="btn whatsapp">💬 WhatsApp</a>
<a href="https://instagram.com/tumcha_id" class="btn instagram">📸 Instagram</a>
</div>
<div class="footer">NFC Tap करून Connect झालात! ✨</div>
</div>
</body>
</html>
