<!DOCTYPE html>
<html lang="en">

<head>
  <script src="firstfile.js"></script>
  <script>
    function annotateUrl() {
      var toDrop = ['titan'];
      var toAdd = { wellActually: 'CRAYONS' };
      return {
        include: toAdd
      };
    };
  </script>
  <script>
    (function (apiKey) {
      (function (p, e, n, d, o) {
        var v, w, x, y, z;
        o = p[d] = p[d] || {};
        o._q = [];
        v = ['initialize', 'identify', 'updateOptions', 'pageLoad', 'track'];
        for (w = 0, x = v.length; w < x; ++w)
          (function (m) {
            o[m] = o[m] || function () {
              o._q[m === v[0] ? 'unshift' : 'push']([m].concat([].slice.call(arguments, 0)));
            };
          })(v[w]);
        y = e.createElement(n);
        y.async = !0;

        y.src = 'https://cdn.pendo.io/agent/static/' + apiKey + '/pendo.js';
        z = e.getElementsByTagName(n)[0];
        z.parentNode.insertBefore(y, z);
      })(window, document, 'script', 'pendo');
 
      // Call this whenever information about your visitors becomes available
      // Please use Strings, Numbers, or Bools for value types.
      pendo.initialize({
        //excludeAllText: true,
        //DisableGuides: True,
        visitor: {
          id: user_id,   // Required if user is logged in
          email: user_email, // Recommended if using Pendo Feedback, or NPS Email
          full_name: user_full_name,// Recommended if using Pendo Feedback
          language: "en_GB",
          random: user_random_data
          //boolean:      user_boolean
          //date1:        user_date1
          //date2:        user_date2
        },

        account: {
          id: user_account_id, // Highly recommended
          type: user_account_type// Optional
        },

        parentAccount: {
          id: user_parent_account_id,
          name: user_parent_account_name,
          parentAccountOnly: 'yes'
        },
        annotateUrl: annotateUrl
      });
    })('a93e68a6-46fd-443a-699f-aa31985c066d');
  </script>
  <!--
<script id = "ze-snippet" src = "https://static.zdassets.com/ekr/snippet.js?key=2e7dd840-8a9a-484f-8af0-8802bc2d3d2b"> </script>
-->
  <title>Alisyn's Playground</title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="styles.css">
  <link rel="shortcut icon" type="image/jpg" href="engram.ico" />
</head>

<body>

  <div class="header">
    <h1>Oh hai</h1>
    <p>I am a website</p>
  </div>

  <div class="navbar">
    <a href="index.html" class="active">Home</a>
    <a href="warlock.html">Warlock</a>
    <a href="hunter.html">Hunter</a>
    <a href="titan.html">Crayon-eater</a>
    <div class="dropdown">
      <button class="dropbtn">Special Installs</button>
      <div class="dropdown-content">
        <a href="anonymous.html">Anonymous</a>
        <a href="customInitializes.html">Custom Initializes</a>
        <a href="gtm.html">GTM</a>
        <a href="GTMwVars.html">GTM with Variables</a>
        <a href="locationApi.html">Location API</a>
        <a href="segment.html">Segment</a>
    </div>
    </div>
    <a href="SinglePageSite/index.html" class="right">SinglePage</a>
    <a href="cats.html" class="right">Cats</a>
    <a href="Darkness.html" class="right">Dark</a>
    <a href="training-eu.html" class="right">EU</a>
    <a href="training.html" class="right">Training</a>
  </div>

  <div class="row">
    <div class="side">
      <h2>Stuff</h2>
      <img src="img/rainbowEmblem.png" width="300"><br>
      <img src="img/catEmblem.png" width="300"><br>
      <img src="img/heartEmblem.png" width="300"><br>
      <br>
      <SCRIPT LANGUAGE="JAVASCRIPT">

        var r_text = new Array();
        r_text[0] = "Lorem ipsum nightstalker fatebringer.";
        r_text[1] = "Lorem ipsum witherhoard ikelos.";
        r_text[2] = "Lorem ipsum stasis thunderlord.";

        var i = Math.floor(r_text.length * Math.random());

        document.write(r_text[i]);

      </script>
    </div>
    <div class="main">
      <h2>Destiny!</h2>
      <button onclick="location.href = 'https://www.bungie.com';" id="myButton" class="btn red">Bungo</button>
      <button onclick="location.href = 'https://www.d2checklist.com';" id="myButton"
        class="btn green">D2Checklist</button>
      <button onclick="location.href = 'https://www.destinyitemmanager.com';" id="myButton"
        class="btn default">DIM</button>
      <br>
      <br>

      <iframe src="cats.html" height="800" width="75%" title="Cats" style="border:1px solid black;"></iframe>
      <iframe src="iframe.html" height="800" width="75%" title="iframe" style="border:1px solid black;"></iframe>
    </div>
  </div>

  <div class="footer">
    <h2>Helpful Links</h2>
    <a href="https://www.bungie.com">Bungo</a> |
    <a href="https://www.d2checklist.com">D2 Checklist</a> |
    <a href="https://www.destinyitemmanager.com">DIM</a>
  </div>
</body>

</html>