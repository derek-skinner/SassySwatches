Sassy Swatches  - http://sassyswatch.es
===========

Color library for the Sass css preprocessor. Currently featuring 200 unique colors with memorable real-world variable names.

<a href="https://twitter.com/sassyswatches" class="twitter-follow-button" data-show-count="false" data-size="large">Follow @sassyswatches</a>
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>


#Usage
------------------------------

##1. Setting Up

If your familiar with Sass, this should be a piece of cake. Make sure the main `sassyswatches.scss` file is imported at the very bottom of your `_main.scss` file so it will overwrite any similar color variables you may have in your project from other frameworks, etc.

    @import "/path/to/sassyswatches.scss"
    
    
####1a. Optonal - Bower Install
If your current project uses Bower, you can install Sassy Swatches by using the following command:

    bower install sassy-swatches

##2. Using the Colors

Now here's the fun part. If you want to use a color all you need to do is type in it's variable name. Sassy Swatches was built using memorable, real-world variable names for its colors like $Denim, $LawnGreen, $LightSalmonPink, etc.

	body{
			background-color: $DarkChestnut;
		}

You can use the Sassy Swatches color library with all existing [Sass Color Functions](http://sass-lang.com/documentation/Sass/Script/Functions.html) and Mixins.

Example Functions/Mixins
------------------------------
####Darken & Lighten

These two adjust the Lightness of the color’s HSL values. Sass will parse the hex color variable to hsl, then make the adjustments. You call them on the color with a percentage value between 0 and 100.

    darken($Jade, 10%)
    lighten($WineDregs, 10%)

####Saturate, & Desaturate


These functions adjust the Saturation of the colors HSL values, much like Darken and Lighten adjusted the Lightness. You need to give a percentage value to saturate and desaturate. 

    saturate($TigersEye, 20%)
    desaturate($Amber, 20%)

####Adjust-hue

This adjusts the hue value of HSL the same way all of the others do. Again, it takes a percentage value for the change.

    adjust-hue($OliveDrab, 20%)

####Adding Alpha Transparency

Using our hex color we can do a few things to get it to be a little transparent. We can call hsla, rgba, opacify, and transparentize. All of them accomplish the same thing, just in different ways. I stick to rgba as it comes most naturally to me which takes a color and a value from 0 to 1 for the alpha.

    rgba($AppleGreen, .7)
    

---
Contact me on [twitter](https://twitter.com/derektskinner) and let me know what you end up using this on and if you have any questions.

---

License
------------------------------
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Sassy Swatches</span> is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

Changelog
------------------------------
**v1.1.0**         Brand Colors section is added with 50 colors from popular web brands

**v1.0.3**         Fixed $Chartreuse variable name typo</p>
**v1.0.2**         Fixed typo &amp; cleaned up code</p>
**v1.0.1**         Fixed $Lemon variable typo</p>
**v1.0.0**         Sassy Swatches project is released</p>

**v1.0.0**        Sassy Swatches is released on Github.



[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/derek-skinner/sassyswatches/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

