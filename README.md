##Usage
Download or clone this repo to your  `styleheets`-folder and import `_letter-tracking.scss` to your sass-document.

Ex: inside stylesheets/style.scss
````
@import "photoshop-letter-tracking/"
````

and then `@include` the mixin where you want to use it
````
h1 {
@include letter-tracking(150);
}
````
where `150` is the amount of tracking you have in Photoshop.

This will output the css
````
h1 {
letter-spacing:0.150em;
}
````

###Cheers!

##License

This project is licensed under the MIT license. [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT)