# video-popup
Excellent content is important but sometimes words on a page aren't as impactful as imagery. Pop up video elements can do wonders for both giving your website a human voice while also showcasing a more visually engaging element to your website

Video remains one of the most popular forms of content marketing around -- and it's certainly one of the most beneficial for a website.

 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/d1thm4cq/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container">
  <div class="row">
    <div class="col-sm-12">
      <h1 class="text-center display-4 mt-5">
        Solodev Web Design &amp; Content Management Software
      </h1>
      <p class="text-center mt-5">
        <a href="#headerPopup" id="headerVideoLink" target="_blank" class="btn btn-outline-danger popup-modal">See Why Solodev WXP</a>
      </p>
     <div id="headerPopup" class="mfp-hide embed-responsive embed-responsive-21by9">
      <iframe class="embed-responsive-item" width="854" height="480" src="https://www.youtube.com/embed/qN3OueBm9F4?autoplay=1" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</div>

```

## CSS

All required CSS is contained with styles.css

## JavaScript
<script>
        $( document ).ready(function() {
         $('#headerVideoLink').magnificPopup({
          type:'inline',
          midClick: true // Allow opening popup on middle mouse click. Always set it to true if you don't provide alternative source in href.
        });
          
        });
</script>   

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.0.0/magnific-popup.min.css"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/magnific-popup.js/1.0.0/jquery.magnific-popup.min.js"></script>
