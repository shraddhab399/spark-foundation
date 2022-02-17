<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <link rel="stylesheet" type="text/css" href="css/name.css">

    <title>Basic Banking System</title>

    <style type="text/css">
      body{
	      background-image:url("b2.jpg") ;
	      background-position: center;
	      background-size:cover;
	      height: 100vh;
      }
      .btn{
        position:absolute;
        top:50%;
        left:50%;
      }
      button{
        width:130px;
        height:60px;
        font family:sans-serif;
        font: size 15px;
        font-weight:400;
        border-radius:10px;
        letter-spacing:2px;
        transition: 1.5s;
      }
      button:hover{
        background-color:#f4c2c2;
        color: white;
      }
    </style>

  </head>

  <body>
    <?php
      include 'name.php';
    ?>
      <br>
      <br>
    <div class="container-fluid">
      <div class="row intro py-1">
          <div class="col-sm-12 col-md">
            <div class="heading my-6" >
              <center><h1>Basic Banking System</h1></center>
            </div>
          </div>
        </div>
          <br>
          <br>
          <br>
          <br>
          <br>
        <h3 class="action" ><center><span style="font-family: 'Roboto Slab', serif">Choose An Action</h3></span></center>
          <div class="column activity text-center">
            <div class="col-md act">
              <br>
              <br>
              <br>
              <a href="history.php"><button>Transfer History</button></a>
            </div>
            <div class="col-md act">
              <br>
              <br>
              <br>
              <a href="transfermoney.php"><button> Customers to Transfer</button></a>
            </div>
                  
        </div>
      </div>
      <br>
      <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
    </div>
  </body>
</html>