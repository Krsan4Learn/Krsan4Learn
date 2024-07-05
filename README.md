<!DOCTYPE html>
<html lang="ar">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GitHub Profile Background</title>
<style>
  @keyframes animateBackground {
    0% { background-position: 0 0; }
    100% { background-position: 100% 100%; }
  }

  .background {
    position: relative;
    width: 100%;
    height: 300px;
    background: linear-gradient(45deg, #6fb1fc, #eaf7ff);
    background-size: 400% 400%;
    animation: animateBackground 15s ease infinite;
  }

  .center-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
    color: #fff;
  }

  .center-text h1 {
    margin: 0;
    padding: 0;
    font-size: 2em;
    font-weight: bold;
  }

  .center-text ul {
    list-style: none;
    padding: 0;
  }

  .center-text li {
    font-size: 1.2em;
  }
</style>
</head>
<body>

<div class="background">
  <div class="center-text">
    <h1>My name is Ammar !</h1>
    <ul>
      <li>Ethical Hacker</li>
      <li>virus</li>
      <li>Python</li>
      <li>Bash</li>
    </ul>
  </div>
</div>

</body>
</html>
