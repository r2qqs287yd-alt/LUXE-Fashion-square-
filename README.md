<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxe Fashion</title>
<style>
body {
  font-family: Tahoma, sans-serif;
  text-align: center;
  background: url('background.jpg') no-repeat center center fixed;
  background-size: cover;
  padding: 40px;
  color: white;
  position: relative;
  min-height: 100vh;
  margin: 0;
}

body::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0,0,0,0.55);
  z-index: 0;
}

a {
  position: relative;
  z-index: 1;
  display: block;
  margin: 16px auto;
  padding: 14px 20px;
  width: 250px;
  text-decoration: none;
  color: white;
  border-radius: 6px;
  font-size: 18px;
  font-weight: bold;
  transition: 0.3s ease;
  text-shadow: 0 0 6px rgba(0,0,0,0.6);
}

.instagram { background-color: #E4405F; }
.facebook { background-color: #1877F2; }
.tiktok { background-color: #000000; }

a:hover {
  transform: scale(1.05);
  opacity: 0.9;
}
</style>
</head>

<body>
  <a class="instagram" href="https://www.instagram.com">Instagram</a>
  <a class="facebook" href="https://www.facebook.com">Facebook</a>
  <a class="tiktok" href="https://www.tiktok.com">TikTok</a>
</body>
</html>
