# homework2
<!--DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Index</title>

    --insert bootstrap link (in header, before body)--

    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    
    --insert custom css link--

    <link rel="stylesheet" type="text/css" href="css/style.css">
</head>

--switch code regarding navbar-collapse to "pull-right--

--trouble getting header to expand full page at 767px when items collapse--


    <body>
        <nav class="navbar navbar-expand-lg navbar-white bg-white">
            <div class="container" id="navcontainer">
                <span class="navbar-brand" href="#">Taylor Allen</span>
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"></button>
                        <span class="navbar-toggler-icon"></span>
                    </button>
                <div class="navbar-header navbar-right pull-right" id="navbarNav">
                        <ul class="nav pull-right">
                    <li class="nav-item active">
      
      --dont forget to link other pages to navigation bar--

                      <a class="nav-link" href="index.html">About <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="contact.html">Contact</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="portfolio.html">Portfolio</a>
                    </li>

                    </ul>
                </div>                  
            </div>
        </nav>

        --new container for body - use rows & columns to improve placement when resizing browser--

        <div class="container" id="bodycontainer">
                <div class="row">
                  <div class="col-lg-12">
                    <section id="main-bio">
                      <h2>About Me</h2>
                    </div>
                    <div class="row">
                      <div class="col-lg-12">
                            <img src="images/20190926_000107.jpg" alt="Taylor" width="250" class="img-thumbnail">
                        <p>
                           Writing a bio about yourself can be stressfull if you think to much. Give yourself time for it
                        </p>
                      </div> 
                    </section>
                </div>
            </div>
        </div>

         DONT TOUCH THE FOOTER, SOMEHOW IT ALWAYS GETS MESSED UP.

        <div class="content">
            
        </div>
        <footer class="footer"></footer>
        <footer>
            <p>Copyright ©</p>
        </footer>

        --add javascript--

        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    </body>
  
</html>