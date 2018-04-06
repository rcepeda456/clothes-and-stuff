# clothes-and-stuff
clothing site
<!DOCTYPE html>
<html>
<head>
<style>

    @import url('https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css');

    @import url(https://fonts.googleapis.com/css?family=Lato:400,300,900,700);

    html {
      font-size: 16px;
    }
    * {
    box-sizing: border-box;
}

.column {
    float: left;
    width: 33.33%;
    padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
    content: "";
    clear: both;
    display: table;

    h3 {
      font-family: 'Lato', sans-serif;
      font-size: 2.125rem;
      font-weight: 700;
      color: #444;
      letter-spacing: 1px;
      text-transform: uppercase;
      margin: 55px 0 35px;
    }

    a {
      color: #ddd;
      text-transform: capitalize;
      font-size: 20px;
      &:hover {
        color: #ccc;
        text-decoration:none;
      }
    }

    .carousel-inner { margin: auto; width: 100%; }
    .carousel-control            { width:  4%; }
    .carousel-control.left,
    .carousel-control.right {
      background-image:none;
    }

    .glyphicon-chevron-left, .carousel-control .glyphicon-chevron-right {
      margin-top:-10px;
      margin-left: -10px;
      color: #444;
    }

    .carousel-inner {
      a {
        display:table-cell;
        height: 180px;
        width: 200px;
        vertical-align: middle;
      }
      img {
        max-height: 150px;
        margin: auto auto;
        max-width: 100%;
      }
    }

    @media (max-width: 767px) {
      .carousel-inner > .item.next,
      .carousel-inner > .item.active.right {
          left: 0;
          -webkit-transform: translate3d(100%, 0, 0);
          transform: translate3d(100%, 0, 0);
      }
      .carousel-inner > .item.prev,
      .carousel-inner > .item.active.left {
          left: 0;
          -webkit-transform: translate3d(-100%, 0, 0);
          transform: translate3d(-100%, 0, 0);
      }

    }
    @media (min-width: 767px) and (max-width: 992px ) {
      .carousel-inner > .item.next,
      .carousel-inner > .item.active.right {
          left: 0;
          -webkit-transform: translate3d(50%, 0, 0);
          transform: translate3d(50%, 0, 0);
      }
      .carousel-inner > .item.prev,
      .carousel-inner > .item.active.left {
          left: 0;
          -webkit-transform: translate3d(-50%, 0, 0);
          transform: translate3d(-50%, 0, 0);
      }
    }
    @media (min-width: 992px ) {

      .carousel-inner > .item.next,
      .carousel-inner > .item.active.right {
          left: 0;
          -webkit-transform: translate3d(16.7%, 0, 0);
          transform: translate3d(16.7%, 0, 0);
      }
      .carousel-inner > .item.prev,
      .carousel-inner > .item.active.left {
          left: 0;
          -webkit-transform: translate3d(-16.7%, 0, 0);
          transform: translate3d(-16.7%, 0, 0);
      }

    }
    .news_img{
  margin:0 20 0 20;
  float:left;
}
.trailer_button{
    z-index:999;
    float:left;
    margin:1 20 -20 20;
    width:181px;
    border-radius:10px;
}
.buttonimg{
    width:auto;
    height:auto;
}



</style>
<body>
  <a href="webproject1.html"> Mens  </a> || <a href="wpg.html">Womens </a> || <a href="uoa.html"> Accessories </a>
  <div class="row">
    <div class="column">
      <img src="UOmaletops.jpg" alt="Mens Tops" style="width:100%">
    </div>
    <div class="column">
      <img src="uobottomM.jpeg" alt="Mens Bottom" style="width:100%">
    </div>
    <div class="column">
      <img src="outwearmens.jpeg" alt="Outterwear" style="width:100%">
    </div>
  </div>


<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>


<div class="col-md-12 text-center"><h3>Mens Tops</h3></div>
<div class="col-md-10 col-md-offset-1">
<div class="carousel slide" data-ride="carousel" data-type="multi" data-interval="3000" id="myCarousel">
  <div class="carousel-inner">
    <div class="item active">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="Uomaletops.jpg" class="img-responsive"<p>
      Orange Long sleeve <br>
        $19.99</p></a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot1.jpg" class="img-responsive"<p>
        Colorful strip short sleeve hoodie <br>
        $18.99</p></a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot2.jpeg" class="img-responsive"<p>
        Red and Black long sleeve <br>
        $24.99</p></a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot3.jpeg" class="img-responsive"<p>
        Levis white t-shirt <br>
        $9.00</p></a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot4.jpeg" class="img-responsive"<p>
        Strip color hoodie<br>
        $26.99
      </p></a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot5.jpeg" class="img-responsive"<p>
      Olive green pocket t-shirt<br>
      $10.99
    </p></a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot6.jpeg" class="img-responsive"<p>
      Brown fleece long sleeve <br>
      $29.00</a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uot7.jpg" class="img-responsive"><p>
      Olive pocket t-shirt <br>
      $29.00</a></div>
      </a></div>
    </div>
  </div>
  <a class="left carousel-control" href="#myCarousel" data-slide="prev"><i class="glyphicon glyphicon-chevron-left"></i></a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next"><i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>

<div class="col-md-12 text-center"><h3>Mens Bottom</h3></div>
<div class="col-md-10 col-md-offset-1">
<div class="carousel slide" data-ride="carousel" data-type="multi" data-interval="3000" id="myCarousel">
  <div class="carousel-inner">
    <div class="item active">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob2.jpeg" class="img-responsive"<p>
        slim ripped jeans<br>
        $16.99
      </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob1.jpeg" class="img-responsive"<p>
      Classic slim chinos<br>
      $20.99
    </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob8.jpeg" class="img-responsive"<p>
      Vintage dark blue ripped Overalls <br>
      $36.99
    </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob3.jpeg" class="img-responsive" <p>
        Classic straight jeans<br>
        14.99
      </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob7.jpg" class="img-responsive"<p>
      slim fit jeans<br>
      $14.99
    </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob5.jpg" class="img-responsive"<p>
        Skinny fit jeans<br>
        $19.99
      </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob6.jpg" class="img-responsive"<p>
      Regular sweats<br>
      10.99
  </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uob7.jpg" class="img-responsive"<p>
      Chill sway joggers<br>
     20.99
  </a></div>
    </div>
  </div>
  <a class="left carousel-control" href="#myCarousel" data-slide="prev"><i class="glyphicon glyphicon-chevron-left"></i></a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next"><i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>


<div class="col-md-12 text-center"><h3>Outerwear</h3></div>
<div class="col-md-10 col-md-offset-1">
<div class="carousel slide" data-ride="carousel" data-type="multi" data-interval="3000" id="myCarousel">
  <div class="carousel-inner">
    <div class="item active">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo.jpeg" class="img-responsive"<p>
        Light blue slim jean jacket<br>
        34.99
      </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo1.jpeg" class="img-responsive"<p>
        Sway fur jacket<br>
        69.99
      </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo8.jpg" class="img-responsive"<p>
        Vest rain jacket<br>
        $32.00
      </a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo3.jpeg" class="img-responsive"<p>
      Half zip windbreaker<br>
      $42.99</a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo4.jpg" class="img-responsive"<p>
      Rain jacket <br>
      89.99</a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo5.jpg" class="img-responsive"<p>
      Leather biker jacket<br>
      $54.99</a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo6.jpeg" class="img-responsive"<p>
      Oversize  sway coat
     $102.00</a></div>
    </div>
    <div class="item">
      <div class="col-md-2 col-sm-6 col-xs-12"><a href="#"><img src="uoo7.jpeg" class="img-responsive"<p>
      Fleece heavy Jacket<br>
      $82.99</a></div>
    </div>
  </div>
  <a class="left carousel-control" href="#myCarousel" data-slide="prev"><i class="glyphicon glyphicon-chevron-left"></i></a>
  <a class="right carousel-control" href="#myCarousel" data-slide="next"><i class="glyphicon glyphicon-chevron-right"></i></a>
</div>
</div>

 <script>
     $(document).ready(function() {
        $('.carousel[data-type="multi"] .item').each(function(){
          var next = $(this).next();
          if (!next.length) {
            next = $(this).siblings(':first');
          }
          next.children(':first-child').clone().appendTo($(this));

          for (var i=0;i<4;i++) {
            next=next.next();
            if (!next.length) {
                next = $(this).siblings(':first');
            }

            next.children(':first-child').clone().appendTo($(this));
          }
        });


    });
</script>
</body>
</html>
