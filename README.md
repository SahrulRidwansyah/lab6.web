# lab6.web

```
Sahrul Ridwansyah
312210063
```

# code html
```
<!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    <title>Web Framework</title>
</head>

<body title="MADE BY MUHAMMAD VERDY HASAN">
    <!-- Container -->
    <div class="container shadow-lg">
        <div class="card-body">
            <h1 class="text-muted py-3">Layout Sederhana</h1>
        </div>
        <!-- Navigasi -->
        <nav class="navbar" style="background-color: #1f5faa;">
            <ul class="nav nav-pills">
                <li class="nav-item">
                    <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">Article</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">Contact</a>
                </li>
            </ul>
        </nav>
        <!-- card section description -->
        <div class="card" style="width: 80,1rem; padding: 50px 20px; background-color: #e4e4e5; border-radius: 0;">
            <div class="card-body">
                <h1 class="card-title pb-4" style="font-weight: bold;">Hello World!</h1>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem saepe
                    necessitatibus aspernatur nisi autem delectus excepturi nostrum natus similique beatae
                    reiciendis, quos placeat sapiente qui sint voluptatibus, a temporibus quasi.</p>
                <a href="#" class="btn btn-primary">Learn More »</a>
            </div>
        </div>
        <!-- Row Content 1 -->
        <div class="row">
            <!-- card 1 -->
            <div class="col-3">
                <div class="col mt-4">
                    <div class="card" style="width: 18rem; border: 0;">
                        <img src="https://dummyimage.com/120/db7d25/fff.png" class="card-img-top rounded-circle"
                            alt="Herli" style="width: 200px;">
                        <div class="card-body">
                            <h5 class="card-title">Heading</h5>
                            <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptates,
                                facere.</p>
                            <a href="#" class="btn btn-primary">View detail</a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- card 2 -->
            <div class="col-3">
                <div class="col mt-4">
                    <div class="card" style="width: 18rem; border: 0;">
                        <img src="https://dummyimage.com/120/3e73e6/fff.png" class="card-img-top rounded-circle"
                            alt="Herli" style="width: 200px;">
                        <div class="card-body">
                            <h5 class="card-title">Heading</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio,
                                magnam?</p>
                            <a href="#" class="btn btn-primary">View detail</a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- card 3 -->
            <div class="col-3">
                <div class="col mt-4">
                    <div class="card" style="width: 18rem; border: 0;">
                        <img src="https://dummyimage.com/120/71e6d4/fff.png" class="card-img-top rounded-circle"
                            alt="Herli" style="width: 200px;">
                        <div class="card-body">
                            <h5 class="card-title">Heading</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, neque.
                            </p>
                            <a href="#" class="btn btn-primary">View detail</a>
                        </div>
                    </div>
                </div>
            </div>
            <!-- Widget Header -->
            <div class="col-3">
                <div class="list-group my-4" style="border-radius: 0;">
                    <a href="#" class="list-group-item list-group-item-action active" aria-current="true"
                        style="font-weight: bold;">
                        Widget Header
                    </a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                </div>
                <!-- Widget Text -->
                <div class="list-group my-4" style="border-radius: 0; border: 1px #eee;">
                    <a href="#" class="list-group-item list-group-item-action active " aria-current="true"
                        style="font-weight: bold;">
                        Widget Text
                    </a>
                    <a href="#" class="list-group-item list-group-item-action">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam quas natus, amet ab
                            voluptatibus beatae accusamus, quam hic veritatis ipsa, accusantium est nihil dolores minus
                            at labore sapiente autem vero.</p>
                    </a>
                </div>
            </div>
        </div>
        <!-- Row Content 2 -->
        <div class="row">
            <!-- Section 1 -->
            <div class="col-8-md">
                <div class="card mb-3" style="width: 900px; height: 200px;  border: 0;">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start"
                                alt="...">
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h2 class="card-title" style="font-weight: bold;">First featurette heading</h2>
                                <p class="card-text" style="text-align: left;">This is a wider card with supporting text
                                    below as a
                                    natural lead-in to additional
                                    content. This content is a little bit longer. Lorem, ipsum dolor sit amet
                                    consectetur adipisicing
                                    elit. Velit animi quidem facere neque. Ea rem labore dolorum, necessitatibus quod,
                                    maiores tempore
                                    harum fugit qui accusantium iure. Dolorum illo repellat vitae?</p>
                                <p class="card-text"><small class="text-muted"></small></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Row Content 3 -->
        <div class="row">
            <!-- Section 2 -->
            <div class="col-8-lg me-5">
                <div class="card mb-3" style="width: 900px; height: 200px; border: 0;">
                    <div class="row g-0">
                        <div class="col-md-8">
                            <div class="card-body">
                                <h2 class="card-title" style="font-weight: bold;">First featurette heading</h2>
                                <p class="card-text">This is a wider card with supporting text below as a natural
                                    lead-in to additional
                                    content. This content is a little bit longer. Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit.
                                    Animi rerum at facilis nesciunt. Quidem, ullam quod beatae sapiente excepturi, vitae
                                    praesentium ipsa
                                    ab optio, doloribus voluptatem vel atque eveniet necessitatibus?</p>
                                <p class="card-text"><small class="text-muted"></small></p>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start"
                                alt="picture">
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="card-footer text-center" style=" background-color: #1d1d1d; color: #eee;">
            <p>© 2023 - Universitas Pelita Bangsa</p>
        </div>
    </div>


    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
        crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
</body>

</html>
```

# css
```
/* import google font */
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300;0,400;0,600;0,700;0,800;1,300;1,400;1,600;1,700;1,800&display=swap');
@import
url('https://fonts.googleapis.com/css2?family=Open+Sans+Condensed:ital,wght@0,300;0,700;1,300&display=swap');

/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    }
    body {
    line-height:1;
    font-size:100%;
    font-family:'Open Sans', sans-serif;
    color:#5a5a5a;
    }
    #container {
    width: 980px;
    margin: 0 auto;
    box-shadow: 0 0 1em #cccccc;
    }
    /* header */
    header {
    padding: 20px;
    }
    header h1 {
    margin: 20px 10px;
    color: #b5b5b5;
    }

    /* navigasi */
nav {
    display: block;
    background-color: #1f5faa;
    }
    nav a {
    padding: 15px 30px;
    display: inline-block;
    color: #ffffff;
    font-size: 14px;
    text-decoration: none;
    font-weight: bold;
    }
    nav a.active,
    nav a:hover {
    background-color: #2b83ea;
    }

    /* Hero Panel */
#hero {
    background-color: #e4e4e5;
    padding: 50px 20px;
    margin-bottom: 20px;
    }
    #hero h1 {
    margin-bottom: 20px;
    font-size: 35px;
    }
    #hero p {
    margin-bottom: 20px;
    font-size: 18px;
    line-height: 25px;
    }

    /* main content */
#wrapper {
    margin: 0;
    }
#main {
    float: left;
    width: 640px;
    padding: 20px;
    }
    /* widget */
.widget-box {
    border:1px solid #eee;
    margin-bottom:20px;
    }
    .widget-box .title {
    padding:10px 16px;
    background-color:#428bca;
    color:#fff;
    }
    .widget-box ul {
    list-style-type:none;
    }
    .widget-box li {
    border-bottom:1px solid #eee;
}
.widget-box li a {
padding:10px 16px;
color:#333;
display:block;
text-decoration:none;
}
.widget-box li:hover a {
background-color:#eee;
}
.widget-box p {
padding:15px;
line-height:25px;
}
/* sidebar area */
 #sidebar {
    float: left;
    width: 260px;
    padding: 20px;
    }
/* footer */
footer {
    clear:both;
    background-color:#1d1d1d;
    padding:20px;
    color:#eee;
    }
/* box */
.box {
    display:block;
    float:left;
    width:33.333333%;
    box-sizing:border-box;
    -moz-box-sizing:border-box;
    -webkit-box-sizing:border-box;
    padding:0 10px;
text-align:center;
}
.box h3 {
margin: 15px 0;
}
.box p {
line-height: 20px;
font-size: 14px;
margin-bottom: 15px;
}
box img {
border: 0;
vertical-align: middle;
}
.image-circle {
border-radius: 50%;
}
.row {
margin: 0 -10px;
box-sizing: border-box;
-moz-box-sizing: border-box;
-webkit-box-sizing: border-box;
}
.row:after, .row:before,
.entry:after, .entry:before {
content:'';
display:table;
}
.row:after,
.entry:after {
clear:both;
}
.divider {
    border:0;
    border-top:1px solid #eeeeee;
    margin:40px 0;
    }
    /* entry */
    .entry {
    margin: 15px 0;
    }
    .entry h2 {
    margin-bottom: 20px;
}
.entry p {
line-height: 25px;
}
.entry img {
float: right;
border-radius: 5px;
margin-right: 15px;
}
.entry .right-img {
float: left;
}
```


![image](https://github.com/sahrul180304/lab6.web/assets/115526901/472455ed-1615-47eb-93f4-de12dc48e0f2)
![image](https://github.com/sahrul180304/lab6.web/assets/115526901/7f3f47cf-d159-405c-bc9e-396e31e31c9e)
![image](https://github.com/sahrul180304/lab6.web/assets/115526901/8128e762-4602-4a1e-a2c3-2c5298fe258f)


