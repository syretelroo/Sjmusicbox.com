# Sjmusicbox.com
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

  <style>
    /* Rest of the CSS remains the same */
  </style>
  <title>SJ Music Box</title>
</head>

<body>
  <nav class="black">
    <div class="nav-wrapper">
      <div class="container">
        <a href="#!" class="brand-logo">SJ Music Box</a>
      </div>
    </div>
  </nav>
  <br>
  <section>
    <div class="container">
      <!-- Commented out the Log in and Log out buttons -->
      <!-- <p id="login-text">Log in with Google</p> -->
      <!-- <button class="btn red" id="authorize-button">Log in</button> -->
      <!-- <button class="btn red" id="signout-button">Log out</button> -->
      <br>
      <div id="content">
        <div class="row">
          <div class="col s6"></div>
          <form id="channel-form">
            <div class="input-field">
              <input type="text" placeholder="Enter channel name" id="channel-input">
              <input type="submit" value="Get Channel data" class="btn grey lighten-2">
            </div>
          </form>
        </div>
        <div id="channel-data" class="col s6"></div>
        <div class="row" id="video-container"></div>
      </div>
    </div>
  </section>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
  <script src="main.js"></script>
  <script async defer src="https://apis.google.com/js/api.js" onload="handleClientOnLoad()" onreadystatechange="if (this.readyState === 'complete') this.onload();">
  </script>
  <script>
    function handleClientOnLoad() {
      // Hide the Log in and Log out buttons
      // const loginBox = document.getElementById('login-text');
      // const authorizeButton = document.getElementById('authorize-button');
      // const signoutButton = document.getElementById('signout-button');
      // loginBox.style.display = 'none';
      // authorizeButton.style.display = 'none';
      // signoutButton.style.display = 'none';
    }
  </script>
</body>

</html>
