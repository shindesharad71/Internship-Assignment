<template>
    <!-- Static navbar -->
    <nav class="navbar navbar-default navbar-fixed-top">
        <div class="container-fluid">
          <div class="navbar-header">
            <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
              <span class="sr-only">Toggle navigation</span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
              <span class="icon-bar"></span>
            </button>
            <a class="navbar-brand" href="#">
                <img style="max-width:50px; margin-top: -7px;" src="https://bookaholicc.com/images/logo_new.png">
            </a>
          </div>
          <div id="navbar" class="navbar-collapse collapse">
            <ul class="nav navbar-nav">
              <li class="dropdown">
                <a id="shop" href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Product Catalogue <span class="caret"></span></a>
                <ul class="dropdown-menu">
                  <li><a href="#">Action</a></li>
                  <li><a href="#">Another action</a></li>
                  <li><a href="#">Something else here</a></li>
                  <li><a href="#">Separated link</a></li>
                  <li><a href="#">One more separated link</a></li>
                </ul>
              </li>
            </ul>
            <ul class="nav navbar-nav">
              <li class="dropdown">
                <a id="shop" href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Product Catalogue 2<span class="caret"></span></a>
                <ul class="dropdown-menu">
                  <li><a href="#">Action</a></li>
                  <li><a href="#">Another action</a></li>
                  <li><a href="#">Something else here</a></li>
                  <li><a href="#">Separated link</a></li>
                  <li><a href="#">One more separated link</a></li>
                </ul>
              </li>
            </ul>
            <form class="navbar-form navbar-left">
              <div class="input-group">
                <input type="text" class="form-control" placeholder="Search">
                <div class="input-group-btn">
                  <button class="btn btn-default" type="submit">
                    <i class="glyphicon glyphicon-search"></i>
                  </button>
                </div>
              </div>
            </form>
            <ul class="nav navbar-nav navbar-right">
              <li class="dropdown">
                <a id="shop" href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">EU<span class="caret"></span></a>
                <ul class="dropdown-menu">
                  <li><a href="#">AB</a></li>
                  <li><a href="#">CD</a></li>
                  <li><a href="#">INR</a></li>
                  <li><a href="#">$</a></li>
                </ul>
              </li>
              <li id="shop"><i class="glyphicon glyphicon-shopping-cart"></i>123</li>
            </ul>
          </div><!--/.nav-collapse -->
        </div><!--/.container-fluid -->
      </nav>
</template>

<style scoped>
.navbar {
    border-radius: 0px;
    background-color: #2E2E2E;
    border-color: #2E2E2E;
    margin-bottom: 0px;
    min-height: 60px;
    color: #fcfcfc;
}

.nav>li {
  margin-bottom: 0px;
}

.nav>li:focus, .nav>li:hover, .nav>li:active {
  color: #fcfcfc;
  background-color: #CF003A
}

.nav>li>a:focus, .nav>li>a:hover, .nav>li>a:active {
  color: #fcfcfc;
  background-color: #CF003A
}

.nav>li>a {
  font-size: 18px;
   color: #fcfcfc;
}

#shop {
  padding: 20px 30px;
  display: block;
  font-size: 20px;
  border-left: 1px solid #cccccc;
  border-right: 1px solid #cccccc;
}

input {
  background-color: #2E2E2E;
}

button {
  background-color: #2E2E2E;
  color: #cccccc;
  border-left: none;
}

button:hover, button:active {
  background-color: #2E2E2E;
  color: #cccccc;
  border-left: none;
}
</style>
