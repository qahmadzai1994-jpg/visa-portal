<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pakistan Visa Application Portal</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, sans-serif;
}

body{
  background:#f2f2f2;
}

/* ===== HEADER ===== */
.header{
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:10px 14px;
  background:#ffffff;
  border-bottom:1px solid #ddd;
}

.logo-box{
  display:flex;
  align-items:center;
  gap:10px;
}

.logo-box img{
  height:40px;
  display:block;
}

.portal-title{
  line-height:1.2;
}

.portal-title .main{
  font-size:14px;
  color:#555;
  font-weight:600;
}

.portal-title .sub{
  font-size:11px;
  color:#888;
}

.menu-btn{
  font-size:26px;
  cursor:pointer;
}

/* ===== MENU ===== */
#menu{
  display:none;
  background:#fff;
  border-bottom:1px solid #ddd;
}

#menu a{
  display:block;
  padding:12px;
  text-decoration:none;
  color:#000;
  border-top:1px solid #eee;
}

/* ===== CONTENT ===== */
.card{
  max-width:420px;
  margin:0 auto;
  background:#fff;
  padding:18px;
  text-align:center;
}

.ref{
  color:#0a7dbd;
  font-size:18px;
  font-weight:bold;
  margin:12px 0;
}

.photo img{
  width:140px;
  height:180px;
  object-fit:cover;
  border:1px solid #ccc;
  margin:10px 0;
}

/* ===== TEXT ===== */
.label{
  color:#888;
  font-size:13px;
  margin-top:12px;
}

.value{
  font-size:16px;
  margin-top:3px;
}

/* ===== LOGOUT ===== */
.logout{
  max-width:420px;
  margin:15px auto;
  background:#0a7dbd;
  color:#fff;
  padding:12px;
  text-align:center;
  border-radius:3px;
  cursor:pointer;
}

/* ===== FOOTER NOTE ===== */
.footer-note{
  max-width:420px;
  margin:10px auto 20px;
  text-align:center;
  font-size:11px;
  color:#888;
}

/* ===== PRINT (PDF) ===== */
@media print{
  .menu-btn,
  #menu,
  .logout{
    display:none !important;
  }
}
</style>
</head>

<body>

<!-- ===== HEADER ===== -->
<div class="header">
  <div class="logo-box">
    
    <!-- LOGO (Base64) -->
    <img src="data:image/jpeg;base64,LOGO_BASE64_HERE">

    <div class="portal-title">
      <div class="main">Pakistan Visa Application Portal</div>
      <div class="sub">Online Visa Application & Verification</div>
    </div>

  </div>

  <div class="menu-btn" onclick="toggleMenu()">☰</div>
</div>

<!-- ===== MENU ===== -->
<div id="menu">
  <a href="#">Home</a>
  <a href="#">Visa Status</a>
  <a href="#">Contact</a>
</div>

<!-- ===== CONTENT ===== -->
<div class="card">

  <div class="ref">
    Visa Reference Number<br>
    88006011480
  </div>

  <div class="photo">
    <!-- PHOTO (Base64) -->
    <img src="data:image/jpeg;base64,PHOTO_BASE64_HERE">
  </div>

  <div class="label">NAME</div>
  <div class="value">Safi Mudasir</div>

  <div class="label">Passport No</div>
  <div class="value">P05926591</div>

  <div class="label">Passport Country</div>
  <div class="value">Afghanistan</div>

  <div class="label">Visa Category</div>
  <div class="value">Tourist / Visit</div>

  <div class="label">Visa Sub Category</div>
  <div class="value">Individual (Less Than 3 Months)</div>

  <div class="label">Application Type</div>
  <div class="value">Entry</div>

  <div class="label">Staying Facility</div>
  <div class="value">Multiple Entry – Upto 1 Year</div>

  <div class="label">Visa Start Date</div>
  <div class="value">21 Dec 2025</div>

</div>

<!-- ===== LOGOUT ===== -->
<div class="logout" onclick="logout()">Logout</div>

<!-- ===== FOOTER ===== -->
<div class="footer-note">
This portal is for application tracking and verification purposes only.
</div>

<script>
function toggleMenu(){
  var m = document.getElementById("menu");
  m.style.display = (m.style.display === "block") ? "none" : "block";
}

function logout(){
  alert("Logged out successfully");
}
</script>

</body>
</html>
</body>
</html>
  <h3>Sample Photo:</h3>
  <img src="photo.jpg" width="220">
</div>

</body>
</html>
