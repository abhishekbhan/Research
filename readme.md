# Sass
##(Syntactically Awesome StyleSheets)

Sass is an extension of CSS that adds power and elegance to the basic language.

Sass helps keep large stylesheets well-organized, and get small stylesheets up and running quickly, particularly with the help of the Compass style library.

  - CSS3 compatible
  - Awesome syntax with nesting 
  - Has useful extensions like variables, functions and directives
  
  Sass website has amazing documentation and they go over all the feature in great detail with nice examples. You can find the documentation here: [sass]
  
  
  Some cool features:
  
  - Sass supports partial Sass files(_filename.scss) which other style sheets can use by @import
  
  - @extend allows you to import all the styling from one div/class to another
  
  - Sass also allows you to have conditional statements wich can control the CSS if the conditionals return true or false
  
  - Users can define their own Sass functions using the Ruby API.
  
  - Declare custom functions to add customization to you style sheets! Check the documentation here: [customfunctions]
  
  ---
  
  
# CSS Animations

CSS3 has a lot of animations/ transitions that can replace simple javascript and Flash animations.

Simple Javascript animation example:
<pre><code>
$("button").click(function(){
    $("#div1").fadeIn();
    $("#div2").fadeIn("slow");
    $("#div3").fadeIn(3000);
});
</code></pre>

Similary CSS animations can be written in the same way in your style sheets:
<pre><code>
div {
    -webkit-animation: myfirst 5s; /* Chrome, Safari, Opera */
    animation: myfirst 5s;
}

/* Chrome, Safari, Opera */
@-webkit-keyframes myfirst {
    from {background: red;}
    to {background: yellow;}
}

/* Standard syntax */
@keyframes myfirst {
    from {background: red;}
    to {background: yellow;}
}
</pre></code>  
 
 Checkout [w3c] if you want to test some basic animations and play with the different setting you can apply to them.
 
 
 Another great source of reference to learn CSS animations: [MDN]
  
 Check out these awesome animations that developers made entirely using CSS3 animations!!! [awesomeCSS]
 
  ---
  There are a lot of premade open source libraries you can download from github and use them for your projects like :
  
  - Animate.css
  
  - Magic CSS3 animations
  
  Codegeekz has a few other examples you can check out if you want!
  
  
  
  
  [sass]:http://sass-lang.com/documentation/file.SASS_REFERENCE.html#how_it_works
  [customfunctions]: http://sass-lang.com/documentation/Sass/Script/Functions.html#adding_custom_functions
  [w3c]:http://www.w3schools.com/css/css3_animations.asp
  [MDN]:https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes
  [awesomeCSS]:http://www.creativebloq.com/css3/animation-with-css3-712437