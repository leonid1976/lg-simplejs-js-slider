<h2>A simple, responsive, slider</h2><br><br>
Simple slider that can be used for most projects. Using almost only CSS (transitions, transform and such) it's super easy to setup and very lightweight.<br><br>
It's not depending on jQuery. Just vanilla javascript <br><br>
Feel free to use it in your projects; do whatever you want.<br><br>
<h3>Bugs?</h3><br><br>
Please submit an issue, or should you have the solution; make a pull request please.<br><br>

HTML Markup

      <div class="slider myslider__outer">
       <div class="myslider">
          <div class="dish__items myslider__wrapper">
           <div class="myslider__item">   
              ....... <!-- Any html code of one slier-->
          </div>      
           <div  class="myslider__item">
              ....... <!-- Any html code of one slier-->
          </div>      <!--myslide__item-end-->
            
              .....................
                  
          </div>     <!--wrapper-->            
          </div>     <!--mySlider-->            

      <div class="myslider__control myslider__control_left myslider__control_show" role="button">
        &#60;
      </div>
      <div class="myslider__control myslider__control_right myslider__control_show" role="button">
        &#62;
      </div> 

     </div> <!--slider-->



<h3>Using</h3>
<link rel="stylesheet" href="lg-simple-js-slider.css"><br><br>
<script type="text/javascript" src="lg-simple-js-slider.js "></script><br><br>

<script type="text/javascript"><br>
let slider = simpleSlider('.myslider', {<br>
      isCycling: true,<br>
      direction: 'right',<br>
      interval: 2000,<br>
      pause: true<br>
    })<br>
</script>
