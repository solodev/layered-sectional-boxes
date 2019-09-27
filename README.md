# layered-sectional-boxes
Add dimension and focus points by layering title boxes over images .

## Tutorial
For detailed instruction's, view Solodev's [How to Create Layered Sectional Boxes](https://www.solodev.com/blog/how-to-create-layered-sectional-boxes.stml) article.

## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/otdru571/12/).

## HTML

The tutorial contains the following basic HTML markup.

```
<section class="our-people" id="ourPeople">
        <div class="container">
            <div class="row">
                <div class="col-sm-12">
                    <h4 class="lead text-center">If you're an explorer, then the moon is calling. Join the LunarXP mission where new worlds await. </p>
                </div>
            </div>
            <div class="row">
                <div class="col-sm-12">
                    <img alt="our people hero" class="img-fluid mx-auto desktop-img" src="images/astronaut.jpg">
                    <img alt="our people hero" class="img-fluid mx-auto mobile-img" src="images/astronaut-mobile.png">
                </div>
            </div>
            <div class="row pb-sm-5">
          <div class="col-sm-5 text-white">
                <img alt="blue star box" class="img-fluid mx-sm-auto box p-sm-5" src="images/lunarxp-square-logo.png">
              <h3 class="text-uppercase">Our People</h3>
          </div>
                <div class="col-sm-7">
                    <div class="intro">
                        <p>Talent. Dedication. Heart. Meet the team of talented people that are leading our exploration of the moon and beyond.</p>
                        <p><a class="text-red link text-uppercase font-weight-bold" href="http://www.lunarxp.com/">Learn about LunarXP</a></p>
                    </div>
                </div>
            </div>
        </div>
    </section>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
```