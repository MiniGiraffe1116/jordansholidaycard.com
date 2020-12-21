
<html>
  <head>
    <link href="https://fonts.googleapis.com/css?family=Archivo+Narrow|Cookie&display=swap" rel="stylesheet">
    <style>
    #snow {
		position: fixed;
		top: 0;
		left: 0;
		right: 0;
		bottom: 0;
		pointer-events: none;
		z-index: 1000;
		}

    body {
      width: 100%;
      height: 100vh;
      perspective: 1200px;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      background-image: url('https://gdurl.com/btx3');
      background-size: cover;
    }

    .card {
      transform-style: preserve-3d;
      position: relative;
      height: 200px;
      cursor: pointer;
    }

    h1 {
      font-family: 'Cookie', serif;
      font-size: 40px;
      margin-top: 40px;
      color: Red;
    }

    h5 {
      font-family: 'Cookie', serif;
    }

    p {
      font-size: 10px;
    }

    img{
      margin-top: 60px;
      width: 90px;
      transform: scaleX(-1);
    }

    .page, .front {
      background: url('https://www.thesprucecrafts.com/thmb/sooPnT6wjK3cWhA-0a4WJDqsRIc=/4000x2666/filters:fill(auto,1)/free-christmas-card-templates-1356280_FINAL-75b7dcc66518476bbbc20e577127d0c3.png') no-repeat center darkred;
      background-size: cover;
    }

    .message {
      margin-top: 30px;
      color: #900909;
    }

    .front, .back, .page {
      transform-style: preserve-3d;
      transform-origin: left center;
      transition: transform .5s ease-in-out, box-shadow .5s ease-in-out;
      position: absolute;
      width: 120px;
      height: 100%;
      top: 0; 
      left: 0;
      background-color: #F7F7F7;
      padding: 40px;
    }

    .card:hover .front {
      transform: rotateY(-160deg);
      box-shadow: 0 1em 3em 0 rgba(0, 0, 0, .2);
    }

    .card:hover .page {
      transform: rotateY(-159deg);
      box-shadow: 0 1em 3em 0 rgba(0, 0, 0, .2);
    }

    .card:hover .back {
      transform: rotateY(-20deg);
      box-shadow: 0 1em 3em 0 rgba(0, 0, 0, .2);
    }
    </style>
  </head>
  <body>
  <script>
document.addEventListener('DOMContentLoaded', function(){
    var script = document.createElement('script');
    script.src = 'https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js';
    script.onload = function(){
        particlesJS("snow", {
            "particles": {
                "number": {
                    "value": 200,
                    "density": {
                        "enable": true,
                        "value_area": 800
                    }
                },
                "color": {
                    "value": "#ffffff"
                },
                "opacity": {
                    "value": 0.7,
                    "random": false,
                    "anim": {
                        "enable": false
                    }
                },
                "size": {
                    "value": 5,
                    "random": true,
                    "anim": {
                        "enable": false
                    }
                },
                "line_linked": {
                    "enable": false
                },
                "move": {
                    "enable": true,
                    "speed": 5,
                    "direction": "bottom",
                    "random": true,
                    "straight": false,
                    "out_mode": "out",
                    "bounce": false,
                    "attract": {
                        "enable": true,
                        "rotateX": 300,
                        "rotateY": 1200
                    }
                }
            },
            "interactivity": {
                "events": {
                    "onhover": {
                        "enable": false
                    },
                    "onclick": {
                        "enable": false
                    },
                    "resize": false
                }
            },
            "retina_detect": true
        });
    }
    document.head.append(script);
});

</script>
<div id="snow"></div>

    <div class="card">
      <div class="back">
          <div class="message">
            <h5>Dear Mother and Father,</h5>
            <p>This is a holiday card. Please enjoy my holiday card. That is all have a nice day. </p>
            <h5 class="cookie">Your child, Me.</h5>
          </div>
      </div>
      <div class="page">
          <img src="https://gdurl.com/bDCk">
      </div>
      <div class="front">
          <h1>Merry Hannukah</h1>
      </div>
    </div>
  </body>
</html>
<script type="application/javascript" src="/share.js"></script>
