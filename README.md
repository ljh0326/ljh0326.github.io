<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
    <link rel="stylesheet" href="Mypage.css" type="text/css">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" integrity="sha384-rwoIResjU2yc3z8GV/NPeZWAv56rSmLldC3R/AZzGRnGxQQKnKkoFVhFQhNUwEyJ" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.1.1.slim.min.js" integrity="sha384-A7FZj7v+d/sdmMqp/nOQwliLvUsJfDHW+k9Omg/a/EheAdgtzNs3hpfag6Ed950n" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/tether/1.4.0/js/tether.min.js" integrity="sha384-DztdAPBWPRXSA/3eYEEUWrWCy7G5KFbe8fFjk5JAIxUYHKkDx6Qin1DkWx51bBrb" crossorigin="anonymous"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js" integrity="sha384-vBWWzlZJ8ea9aCX4pEW3rVHjgjt7zpkNpZk+02D9phzyeVkE+jo0ieGizqPLForn" crossorigin="anonymous"></script>
</head>
<body>
    <nav class="navbar navbar-toggleable-md navbar-light navbar navbar-light bar-color" >
      <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <a class="navbar-brand" href="#">Navbar</a>

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Link</a>
          </li>
          <li class="nav-item">
            <a class="nav-link disabled" href="#">Disabled</a>
          </li>
        </ul>
        <form class="form-inline my-2 my-lg-0">
          <input class="form-control mr-sm-2" type="text" placeholder="Search">
          <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
      </div>
</nav>

<!--sector -->
 <div class="sector">
           <video poster="https://s3-us-west-2.amazonaws.com/s.cdpn.io/4273/polina.jpg" id="bgvid" playsinline autoplay muted loop>
          <!-- WCAG general accessibility recommendation is that media such as background video play through only once. Loop turned on for the purposes of illustration; if removed, the end of the video will fade in the same way created by pressing the "Pause" button  -->
        <source src="http://thenewcode.com/assets/videos/polina.webm" type="video/webm">
        <source src="http://thenewcode.com/assets/videos/polina.mp4" type="video/mp4">
        </video>
        <div id="polina">
        <h1>Polina</h1>
        <p>filmed by Alexander Wagner 2011
        <p><a href="http://thenewcode.com/777/Create-Fullscreen-HTML5-Page-Background-Video">original article</a>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur porta dictum turpis, eu mollis justo gravida ac. Proin non eros blandit, rutrum est a, cursus quam. Nam ultricies, velit ac suscipit vehicula, turpis eros sollicitudin lacus, at convallis mauris magna non justo. Etiam et suscipit elit. Morbi eu ornare nulla, sit amet ornare est. Sed vehicula ipsum a mattis dapibus. Etiam volutpat vel enim at auctor.</p>
        <p>Aenean pharetra convallis pellentesque. Vestibulum et metus lectus. Nunc consectetur, ipsum in viverra eleifend, erat erat ultricies felis, at ultricies mi massa eu ligula. Suspendisse in justo dapibus metus sollicitudin ultrices id sed nisl.</p>
        <button>Pause</button>
        </div>
    </div>

  <!-- blog-->
<div class="container">
       <div class="card-deck">
  <div class="card blog">
    <img class="card-img-top" src="http://cfs13.tistory.com/image/15/tistory/2009/02/21/16/04/499fa7970d449" alt="Card image cap">
    <div class="card-block">
      <h4 class="card-title">Card title</h4>
      <p class="card-text">This is a longer card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card blog">
    <img class="card-img-top" src="http://cfs13.tistory.com/image/15/tistory/2009/02/21/16/04/499fa7970d449" alt="Card image cap">
    <div class="card-block">
      <h4 class="card-title">Card title</h4>
      <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
  <div class="card blog">
    <img class="card-img-top" src="http://cfs13.tistory.com/image/15/tistory/2009/02/21/16/04/499fa7970d449" alt="Card image cap">
    <div class="card-block">
      <h4 class="card-title">Card title</h4>
      <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
      <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
    </div>
  </div>
</div>
</div>
    <!-- footer -->
    <div class="footer">
        <p style="text-align:center">copyright by 정훈</p>
    </div>
</body>
</html>