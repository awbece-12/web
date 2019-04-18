<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <link rel="stylesheet" href="bsfiles/css/bootstrap.css">
    <link rel="stylesheet" href="bsfiles/css/fontawesome.css">

</head>
<body>
<!--navbar-->
<nav class="navbar navbar-expand-lg navbar-light bg-dark fixed-top">
    <a href="#" class="navbar-brand"><i class="fas fa-child text-warning fa-2x"></i></a>
    <!-- Brand -->
    <a class="navbar-brand" href="#">navbar</a>

    <!-- Links -->
    <ul class="navbar-nav">
        <li class="nav-item">
            <a class="nav-link text-light text-uppercase" href="#home">home</a>
        </li>
        <li class="nav-item dropdown" data-toggle="dropdown">
            <a class="nav-link text-light text-uppercase "  href="#contact">contact</a>
            <div class="dropdown-menu">
                <a class="dropdown-item" href="">contact1</a>
                <a class="dropdown-item" href="">contact2</a>
            </div>

        </li>
        <li class="nav-item">
            <a class="nav-link text-light text-uppercase" href="#zoom">zoom</a>
        </li>
        <li class="nav-item">
            <a class="nav-link text-light text-uppercase" href="#gallery">gallery</a>
        </li>

    </ul>
    <form class="form-inline">
        <div class="input-group">
            <label for="pswd">password</label>
            <input type="password" class="form-control" id="pswd" name="password"required>
          <button type="submit" class="btn btn-primary">submit</button>
        </div>




    </form>
    
</nav>
<!--end of navbar-->
<!--banner-->
<section>
    <div class="container-fluid">
        <div class="row bg-info justify-content-center align-items-center" style="height: 100vh">
            <div class="col-md-5">
                <h1 class="display-3 text-capitalize"><span class="text-warning">Graphic Pentagram</span><span class="text-green font-weight-bold">Website</span></h1>

                <h2 class="font-weight-light font-italic text-light">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Consequatur culpa magni mollitia saepe voluptas. Adipisci aut consectetur earum molestiae, nihil quas quis temporibus vero? Autem consequuntur delectus deserunt nam placeat.</h2>
                <a href="#" class="btn btn-warning btn-lg">TAP HERE</a>
                <a href="#" class="btn btn-danger btn-lg">TAP HERE</a>

            </div>

        </div>

    </div>


</section>



<br>

<div class="container-fluid" id="home">
    <div class="jumbotron jumbotron-fluid">

        <h1>GAVIN HAIL PUSTON</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam autem debitis earum, illo ipsam neque, perferendis porro quam quo reiciendis reprehenderit unde, voluptatibus? Dolores enim exercitationem ipsa quod saepe veritatis!</p>

    </div>
</div>
<div class="container-fluid" id="gallery">



    <div id="demo" class="carousel slide" data-ride="carousel">
        <ul class="carousel-indicators">
            <li data-target="#demo" data-slide-to="0" class="active"><img src="../../Pictures/2018-11-25/DSC_0263.JPG"/></li>
            <li data-target="#demo" data-slide-to="1"></li>
            <li data-target="#demo" data-slide-to="2"></li>
        </ul>
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="bsfiles/images/car2.jpeg" alt="Los Angeles" width="1100" height="500">
                <div class="carousel-caption">
                    <h3>Hearts On Fire</h3>
                    <p>Classic Sit& Diamond Studs!</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="bsfiles/images/DSC_0263.JPG" alt="Chicago" width="1100" height="500">
                <div class="carousel-caption">
                    <h3>Perricone MD</h3>
                    <p>The Unpeel Blue Zanforn Santa-Alicia</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="bsfiles/images/DSC_0288.JPG" alt="New York" width="1100" height="500">
                <div class="carousel-caption">
                    <h3>New York</h3>
                    <p>We love the Big Apple!</p>
                </div>
            </div>
        </div>
        <a class="carousel-control-prev" href="#demo" data-slide="prev">
            <span class="carousel-control-prev-icon"></span>
        </a>
        <a class="carousel-control-next" href="#demo" data-slide="next">
            <span class="carousel-control-next-icon"></span>
        </a>
    </div>
</div>
</div>

<!--skills-->
<section class="bg-light p-5">
    <div class="container-fluid">
        <!--tittle-->
        <div class="row">
            <div class="col text-center mb-5">
                <h1 class="text-warning display-3">skills</h1>
                <p class="lead text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio hic in laboriosam mollitia nisi, unde. Ad adipisci cumque cupiditate in labore laboriosam libero modi nisi quae, recusandae sint tempore voluptas!</p>

            </div>
        </div>

        <!--end of tittle-->
     <div class="row text-center">
         <div class="col-lg-6 col-sm-11 mx-auto mb-5">
             <i class="fas fa-desktop fa-6x text-warning mb-4"></i>
         <hi class="text-secondary">Emmarging</hi>
         <p class="text-muted my-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam at consequatur corporis doloribus ea eligendi, esse facilis fugiat ipsam maxime minima minus molestiae mollitia nulla officiis possimus quas sit temporibus.</p>
         <a href="" class="btn btn-outline-warning">Learn More</a>
     </div>
         <div class="col-lg-6 col-sm-11 mx-auto mb-5">
             <i class="far fa-edit  fa-desktop fa-6x text-warning mb-4"></i>
             <hi class="text-secondary">Devour</hi>
             <p class="text-muted my-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam at consequatur corporis doloribus ea eligendi, esse facilis fugiat ipsam maxime minima minus molestiae mollitia nulla officiis possimus quas sit temporibus.</p>
             <a href="" class="btn btn-outline-warning">Learn More</a>
         </div>
         <div class="col-lg-6 col-sm-11 mx-auto mb-5">
             <i class="fas fa-cogs fa-6x text-warning mb-4"></i>
             <hi class="text-secondary">Creativity</hi>
             <p class="text-muted my-5">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam at consequatur corporis doloribus ea eligendi, esse facilis fugiat ipsam maxime minima minus molestiae mollitia nulla officiis possimus quas sit temporibus.</p>
             <a href="" class="btn btn-outline-warning">Learn More</a>

         </div>

     </div>
    </div>
</section>




<!--end of skills-->
<!--projects-->
<section class="p-5">
    <div class="container-fluid">
        <!--tittle-->
        <div class="row">
            <div class="col text-center mb-5">
                <h1 class="text-warning display-3">project</h1>
                <p class="lead text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio hic in laboriosam mollitia nisi, unde. Ad adipisci cumque cupiditate in labore laboriosam libero modi nisi quae, recusandae sint tempore voluptas!</p>

            </div>
        </div>

        <!--end of tittle-->
        <div class="row">
            <div class="col-lg-4 col-sm-6 mt-5">
                <img src="bsfiles/images/DSC_0263.JPG" class="img-thumbnail">
                <h2 class="my-4 text-warning">project1</h2>
                <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid at autem beatae, cupiditate, deleniti dolore dolorum est eum fuga fugit harum magnam nam nesciunt nisi quas repellat repellendus saepe sapiente.</p>

            </div>
            <div class="col-lg-4 col-sm-6 mt-5">
                <img src="bsfiles/images/DSC_0263.JPG" class="img-thumbnail">
                <h2 class="my-4 text-warning">project2</h2>
                <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid at autem beatae, cupiditate, deleniti dolore dolorum est eum fuga fugit harum magnam nam nesciunt nisi quas repellat repellendus saepe sapiente.</p>

            </div>
            <div class="col-lg-4 col-sm-6 mt-5">
                <img src="bsfiles/images/DSC_0263.JPG" class="img-thumbnail">
                <h2 class="my-4 text-warning">project3</h2>
                <p class="text-muted">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquid at autem beatae, cupiditate, deleniti dolore dolorum est eum fuga fugit harum magnam nam nesciunt nisi quas repellat repellendus saepe sapiente.</p>

            </div>
        </div>
    </div>
</section>

<!--end of projects-->

<!--team-->
<section class="p-sm-5 p-2 bg-secondary">
    <div class="container-fluid">
        <!--tittle-->
        <div class="row">
            <div class="col text-center mb-5">
                <h1 class="text-warning display-3">Team</h1>
                <p class="lead text-dark">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio hic in laboriosam mollitia nisi, unde. Ad adipisci cumque cupiditate in labore laboriosam libero modi nisi quae, recusandae sint tempore voluptas!</p>

            </div>
        </div>

        <!--end of tittle-->
        <div class="row">
            <div class="col-lg-6 col-sm-10 mx-auto mb-4">
                <div class="card">
                            <img src="bsfiles/images/car2.jpeg" class="card-img-top">
                            <div class="card-body">
                                <div class="card-title">
                                    <h3 class="text-muted">Vipok</h3>
                                </div>
                                <div class="card-subtitle">
                                    <p class="lead text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore laborum necessitatibus tenetur! Animi consequuntur, fugiat ipsa ipsam provident tenetur voluptate. Amet assumenda culpa distinctio doloremque explicabo, molestias quam suscipit vero.</p>
                                </div>
                                <div class="text-right">
                                    <a href="#"><i class="fab fa-facebook fa-2x mx-2 text-primary">F</i></a>
                                    <a href="#"><i class="fab fa-twitter fa-2x mx-2 text-info">T</i></a>
                                    <a href="#"><i class="fab fa-youtube fa-2x mx-2 text-danger">Y</i></a>

                        </div>


                    </div>
                </div>

            </div>
            <div class="col-lg-6 col-sm-10 mx-auto mb-4">
                <div class="card">
                    <img src="bsfiles/images/car2.jpeg" class="card-img-top">
                    <div class="card-body">
                        <div class="card-title">
                            <h3 class="text-muted">Dusit</h3>
                        </div>
                        <div class="card-subtitle">
                            <p class="lead text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore laborum necessitatibus tenetur! Animi consequuntur, fugiat ipsa ipsam provident tenetur voluptate. Amet assumenda culpa distinctio doloremque explicabo, molestias quam suscipit vero.</p>
                        </div>
                        <div class="text-right">
                            <a href=""><i class="fab fa-facebook fa-2x mx-2 text-primary"></i></a>
                            <a href=""><i class="fab fa-twitter fa-2x mx-2 text-info"></i></a>
                            <a href=""><i class="fab fa-youtube fa-2x mx-2 text-danger"></i></a>

                        </div>


                    </div>
            </div>
            <div class="col-lg-8 col-sm-10 mx-auto mb-4">
                <div class="card">
                    <img src="bsfiles/images/car2.jpeg" class="card-img-top">
                    <div class="card-body">
                        <div class="card-title">
                            <h3 class="text-muted">Gwaragwara</h3>
                        </div>
                        <div class="card-subtitle">
                            <p class="lead text-secondary">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Inventore laborum necessitatibus tenetur! Animi consequuntur, fugiat ipsa ipsam provident tenetur voluptate. Amet assumenda culpa distinctio doloremque explicabo, molestias quam suscipit vero.</p>
                        </div>
                        <div class="text-right">

                            <a href="#"><i class="fab fa-facebook fa-2x mx-2">F</i></a>
                            <a href="#"><i class="fab fa-twitter fa-2x mx-2">T</i></a>
                            <a href="#"><i class="fab fa-youtube fa-2x mx-2">Y</i></a>


                        </div>


                    </div>
            </div>
        </div>

    </div>
        </div>
        </div>
 </section>

<!--end of team-->
<!--progress-->
<section class="p-5">
    <div class="container-fluid">
        <!--tittle-->
        <div class="row">
            <div class="col text-center mb-5">
                <h1 class="text-warning display-3">Progress</h1>
                <p class="lead text-dark">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio hic in laboriosam mollitia nisi, unde. Ad adipisci cumque cupiditate in labore laboriosam libero modi nisi quae, recusandae sint tempore voluptas!</p>
            </div>
        </div>

        <!--end of tittle-->
        <div class="row justify-content-center">
            <div class="col-lg-7 col-sm-6 text-secondary">
                <h2>Fiction</h2>
                <div class="progress bg-secondary mb-4">
                    <div class="progress-bar" style="width:60%">
                        60%
                    </div>

                </div>
                <h2>Point Man</h2>
                <div class="progress bg-secondary mb-4">
                    <div class="progress-bar bg-danger" style="width:80%">
                        80%
                    </div>
            </div>
                <h2>Creed</h2>
                <div class="progress bg-secondary mb-4">
                    <div class="progress-bar bg-success" style="width: 100%">
                        100%
                    </div>
                </div>
        </div>
    </div>
        </div>
</section>

<!--end of progress-->
<!--contact-->
<section class="p-6 bg-light">
    <div class="container-fluid">
        <div>
            <!--tittle-->
            <div class="row">
                <div class="col text-center mb-5">
                    <h1 class="text-warning display-3">Contact Us</h1>
                    <p class="lead text-dark">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Distinctio hic in laboriosam mollitia nisi, unde. Ad adipisci cumque cupiditate in labore laboriosam libero modi nisi quae, recusandae sint tempore voluptas!</p>

                </div>

            </div>
            <!--end of tittle-->
            <div class="row justify-content-center">
                <div class="col-lg-7 col-md-9 col-sm-10">
                    <div class="text-center text-secondary">
                        <h2>You Can Haste Any Qst</h2>
                          <p>The Standard Are Compertable</p>
                    </div>
                    <form class="text-muted">
                        <div class="form-group">
                            <label for="name">Name</label>
                            <input type="text" class="form-control" id="name" required>

                        </div>
                        <div class="form-group">
                            <label for="email">Email</label>
                            <input type="text" class="form-control" id="email"required>

                        </div>
                        <div class="form-group">
                            <label for="pswd">Password</label>
                            <input type="text" class="form-control" id="password" required>

                        </div>
                        <div class="form-group">
                            <label for="message">Message</label>
                            <input type="text" class="form-control"  required>
                            <textarea class="form-control" id="Message" cols="30" rows="10"></textarea>

                        </div>
                       <button class="btn btn-outline-warning btn btn-block" type="submit">submit qst</button>
                    </form>

                </div>
            </div>
        </div>
    </div>
</section>

<!--end of contact-->
<!--lagoon-->
<lagoon class="bg-secondary">
    <div class="container">
        <div class="row">
            <div class="col text-center">
                <h1 class="text-black-50 font-weight-light text-capitalize p-4">NEVER DOES NATURE SAY ONE THING AND WISDOM ANOTHER</h1>
                  <h2 class="text-black-50 font-weight-light font-italic mb-4">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam animi aperiam aut distinctio earum, eos, expedita illo libero minus modi molestiae necessitatibus nemo odio placeat quibusdam, reiciendis ullam unde voluptatibus.</h2>

                <div class="py-4">
                    <a href="#"><i class="fab fa-facebook-square fa-3x text-primary mx-4">F</i></a>
                    <a href="#"><i class="fab fa-google-plus fa-3x text-danger mx-4">G</i></a>
                    <a href="#"><i class="fab fa-twitter fa-3x text-info mx-4">T</i></a>
                    <a href="#"><i class="fab fa-youtube fa-3x text-danger mx-4">Y</i></a>

                </div>
                <p class="text-dark py-4 m-0">&copy;copyright 2019-Made by awbece</p>
            </div>

        </div>

    </div>

</lagoon>

<!--end of lagoon-->

<script src="bsfiles/js/jquery.js"></script>
<script src="bsfiles/js/bootstrap.js"></script>

</body>
</html>
