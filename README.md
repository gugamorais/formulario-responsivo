# formulario-responsivo

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style.css" rel="stylesheet">
    <title>formulario</title>
</head>

<body>
    <main class=container>
        <h2>login</h2>
        <form action="">
            <input type="text" name="email" id="email" placeholder="enter your email">
            <input type="password" name="password" id="password" placeholder="your password">
            <input type="submit" value="continue" id="continue">
        </form>
        <footer>
            <span>or conect with your social media</span>
            <div class="socials">


                <a href="https://twitter.com/i/flow/login">
                    <img src="./twitter_3.0.jpg" width="40px" height="40px" id="twitter">
                </a>
                <a href="https://www.facebook.com/login.php/">
                    <img src="./facebook.png" width="40px" height="40px" id="facebook">
                </a>

            </div>

        </footer>
    </main>


</body>

</html>

* {
  margin: 0;
  padding: 0;
  border: 0;
  box-sizing: border-box;
}

body {
  background-color: rgb(83, 39, 83);
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 200px;
}

.container {
  background: lightgrey;
  min-width: 280px;
  min-height: 400px;
  padding: 1.5rem;
  border-radius: 8px;
}

form {
  display: flex;
  flex-direction: column;
}

h2 {
  margin-bottom: 40px;
  font-size: 45px;
  color: rebeccapurple;
}

#email {
  height: 30px;
  margin-bottom: 10px;
  border-radius: 5px;
}

#password {
  height: 30px;
  margin-bottom: 20px;
  border-radius: 5px;
}

#continue {
  height: 40px;
  color: rebeccapurple;
  border-radius: 30px;
  margin-bottom: 20px;
}

span {
  font-size: 20px;
}

.socials {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-evenly;
  margin-top: 30px;
}
