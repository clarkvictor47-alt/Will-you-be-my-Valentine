# Will-you-be-my-Valentine
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Important Question 👀❤️</title>
  <style>
    body {
      background: #ffe6ec;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      text-align: center;
    }

    .box {
      background: white;
      padding: 30px;
      border-radius: 15px;
      box-shadow: 0 10px 20px rgba(0,0,0,0.2);
      max-width: 350px;
    }

    h1 {
      color: #ff3366;
    }

    button {
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      margin: 10px;
    }

    .yes {
      background: #ff3366;
      color: white;
    }

    .no {
      background: #ccc;
    }
  </style>
</head>
<body>

  <div class="box">
    <h1>Hey you 👀❤️</h1>
    <p>I was thinking…<br><br>
       Will you be my Valentine? 🥺💘</p>

    <button class="yes" onclick="yesClicked()">YES 😍</button>
    <button class="no" onclick="noClicked()">No 🙃</button>
  </div>

  <script>
    function yesClicked() {
      document.body.innerHTML = `
        <div style="text-align:center;">
          <h1 style="color:#ff3366;">YAYYY!! 🎉❤️</h1>
          <p>You just made me the happiest person alive 😌💘</p>
          <p>See you on Valentine’s Day 😏🌹</p>
        </div>
      `;
    }

    function noClicked() {
      alert("Wrong answer 😌 Try again.");
    }
  </script>

</body>
</html>
