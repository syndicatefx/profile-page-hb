## About Me

Get instructions on how to install and use [harpjs](http://harpjs.com).

>The static web server with built-in preprocessing.
Harp serves Jade, Markdown, EJS, CoffeeScript, Sass, LESS and Stylus as HTML, CSS & JavaScript—no configuration necessary.
<cite>harpjs.com</cite>

### Get Started

Download or clone this template from the [github repo](http://github.com/syndicatefx/profile-page-hb).

#### Folder Structure

- harp.json
- public
    - css <small>*(includes minified + unminified style.css)*</small>
    - img <small>*(all image assets go here)*</small>
    - _partials <small>*(template blocks)*</small>
    - 404.jade <small>*(the ol' 404 error page)*</small>
    - index.md <small>*(what you are reading right now)*</small>
    - layout.jade <small>*(the main layout)*</small>

#### Usage

Edit __harp.json__ to add __Contact__ and __Social Networks__, your __name__, __job title__, __site name__, __background image url__ and other important meta information. If you're using Google Analytics, you can activate it by changing "analytics" to *true* and adding your unique account ID. 

On the social network links, only the ones you provide an url for will be displayed. I've provided only 8 options here, but you can always add your own icons and other social networks by editing __public/_partials/aside.jade__

The same goes for *user_company* and *user_phone*, they will only show if you provide a value.

- - -
Edit the __public/index.md__ file to insert long form content about you or what ever you want, in markdown format, it will show up in this *slide-in* section.

- - -
Don't forget to replace the images in __public/img/__ with your own:
- avatar.jpg <small>*(keep same name + ext)*</small>
- favicon.ico
- apple-touch-icon.png
- og_image.gif
- bg.jpg <small>*(or what ever you entered in harp.json configuration)*</small>

- - -
If you want to change the design or edit the page's layout, you can always adventure into the __public/css__ and __public/_partials__ folders and explore.

- - -
Thats it, compile with harpjs and upload contents of generated __www/__ folder to your server.

- - -
Let me know how or where you're using it, hit me up [@syndicatefx](https://twitter.com/syndicatefx)