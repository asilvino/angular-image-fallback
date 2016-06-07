Angular Image Fallback <a href="https://github.com/alvarojoao/angular-image-fallback/"><img src="https://img.shields.io/teamcity/codebetter/bt428.svg" alt="Bower version" height="18"></a> <a href="https://github.com/alvarojoao/angular-image-fallback/releases"><img src="https://img.shields.io/badge/Bower-V0.0.1-green.svg" alt="Bower version" height="18"></a>
======================

Angular directives that handles image loading, it has `image-holder` to handle errors in image loading and `image-loading` for placeholder while the image is being loaded.
  
  
  
## Bower Download
`bower install angular-image-fallback`

## Installation
1. Download and import the plugin script.<br />
`<script src="lib/angular-image-fallback/angular.img-fallback.min.js"></script>`
2. Add `angularImgFallback` to your angular app module dependencies list.<br />
`angular.module('myAngularApp', ['angularImgFallback']);`
3. Add the `image` attribute to your img<br />
`<img image="{{'path/to/img.jpg'}}"  />`


## Usage
Just add the `image` attribute to your `<img />` tags<br />
`<img image="{{'path/to/img.jpg'}}"  />`<br />
Make sure you don't use `ng-src` as your image src attribute.


## Advanced options


 - default:<br />
`<img image="{{image.url}}" />`

 - with custom loading placeholder:<br />
`<img image="{{image.url}}" image-loading="/image/loading.gif" />`

 - with custom fallback placeholder:<br />
`<img image="{{image.url}}" image-holder="/image/error.png" />`

 - with custom fallback and loading placeholders:<br />
`<img image="{{image.url}}" image-loading="/image/loading.gif" image-holder="/image/error.png" />`


## Example:

> https://jsfiddle.net/alvarojoao/4wec4gsq/embedded/result/

## Icons license
Icons are provided from http://icomoon.io/ under the GNU General Public License v3.0<br />
http://www.gnu.org/licenses/gpl.html
