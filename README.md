Rippler
==================
Effect that spreads like a wave in touch or click. 

##Example
http://blivesta.github.io/rippler

##Installation
####Step 1: Link required files
~~~ html
<!-- rippler css -->
<link rel="stylesheet" href="dist/css/rippler.min.css">

<!-- vendor js -->
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>

<!-- rippler js -->
<script src="dist/js/rippler.min.js"></script>
~~~

####Step 2: HTML markup
~~~ html
<a class="btn btn-default rippler rippler-inverse" href="#">rippler-inverse</a>
<button class="btn btn-primary rippler rippler-default">rippler-default</button>
~~~

####If you want to change the status for each color. 
~~~ html
<a class="btn btn-link rippler rippler-bs-primary" href="#">...</a>
<a class="btn btn-link text-success rippler rippler-bs-success" href="#">...</a>
<a class="btn btn-link text-info rippler rippler-bs-info" href="#">...</a>
<a class="btn btn-link text-warning btn-lg rippler rippler-bs-warning" href="#">...</a>
<a class="btn btn-link text-danger btn-lg rippler rippler-bs-danger" href="#">...</a>
~~~

####If you want to use the image.
~~~ html
<span class="rippler rippler-img rippler-bs-success">
  <img class="img-responsive" src="image.jpg">
</span>
~~~

####Step 3: Call the rippler
~~~ js
$(document).ready(function() {
  $(".rippler").rippler({
    effectClass      :  'rippler-effect'
    ,effectSize      :  16      // Default size (width & height)
    ,addElement      :  'div'   // e.g. 'svg'(feature)
    ,duration        :  400
  });
}); 
~~~

##License
Released under the MIT license.
