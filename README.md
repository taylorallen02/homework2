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

                      <a class="nav-link" href="file:///C:/Users/Owner/Desktop/BOOTCAMP/homework2/index.html">About <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="file:///C:/Users/Owner/Desktop/BOOTCAMP/homework2/contact.html">Contact</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="file:///C:/Users/Owner/Desktop/BOOTCAMP/homework2/portfolio.html">Portfolio</a>
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
                            Hello Everyone and welcome to my page! I assumed the Bio would be the easiest part of
                            this assignment, however I'm having flashbacks to all the writer's block I used to
                            experience in previous classes and can't seem to find words to make sentences. I've
                            spent the last 8 years overworking myself, traveling whenever possible, and waiting on
                            some higher power to force me down the right path (whatever that is).
            
                            I am the middle child of 5. You are probably assuming that I was the typical
                            "forgotten" child, and you are absolutely right! I didn't received the same level
                            guidance and discipline as my ther siblings, but I don't think I turned out too bad.
                            I've had to learn how to figure a lot of things out on my own, which helped me gain                                 independence, learning skills, and self motivation.

                            My main study over the years has been foreign language, and coding definitely qualifies
                            as a new foreign language to add to my list.
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

        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    </body>
  
</html>