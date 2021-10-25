<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <link rel="stylesheet" href="me.css">
    <a href="https://icons8.com/icon/ZmsyfshyA9PA/menu-squared"></a>
    
</head>
<script>
    
    var menu=document.querySelector("#menu-icon");
    var nav=document.querySelector('.nav');

  
menu.addEventListener('click',()=>{
    if (nav.style.display=="none"){
        nav.style.display="block";
    }
    else{
        nav.style.display="none"
    }
})

</script>
<body>
    <!--my code-->
    <div class="container">
    <!--navbar responsiveness code-->
    
        <div class="menu-icon">

        <img src="menu.png" id="menu-icon">
        </div>

        <!--navbar-->
        <div class="nav">
        <ul class="nav">
            <li class="nav-item">
              <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="about.html" data-toggle=collapse.show>about_me</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link disabled" href="#">contact_me</a>
            </li>
          </ul>
        </div>
</nav>
<!--content-->
<div class="row">

<div class="col-1">
    <img src="programmer.png" class="programmer-icon">
</div>

    
  <a href="about.html"> <button type="button" class="btn btn-outline-dark btn-sm btn-block" >Get started</a>
</button>
  
</div>






<!--bootstrap javascript-->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
</body>

</html>
