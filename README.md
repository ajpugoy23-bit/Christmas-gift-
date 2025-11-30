<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Progressive No Button</title>
<style>
  body {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
    font-family: Arial, sans-serif;
    background-color: #ffe0e0;
    background: url('https://i.imgur.com/lXTomYH.jpg') no-repeat center center fixed;
    background-size: cover;
    font-family: Arial, sans-serif;
  }
  button {
    padding: 15px 90px;
    font-size: 18px;
    margin: 10px;
    border-radius:100px; 
    transition: all 0.3s ease;
    cursor: pointer;
  }
</style>
</head>
<body>

<h1>PLEASE ACCEPT MY GIFT</h1>
<br>
<br>
<br>
<img src="https://i.imgur.com/oUmupW8.png" style="width:500px; height:500px;">
<br>
<br>
<div cls="container">
<button class="yesBtn"><a href="/continue.html" style="text-decoration: none; color: black;">YES</a></button>
<button class="noBtn"><a href="/gift2.html" style="text-decoration: none; color: black;">NO</a></button>
</div>

<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

<script>
// Fire confetti when the page loads
window.onload = () => {
    // Basic burst
    confetti({
        particleCount: 200,
        spread: 100,
        origin: { y: 0.6 }
    });
};
</script>
</body>
</html>
