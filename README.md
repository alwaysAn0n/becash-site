# becash-site

Official Be Cash 2019 Conference Site

Staging at [https://becash-site.herokuapp.com/](https://becash-site.herokuapp.com/)

### Event Description
Here is some information about the Be Cash 2019 Conference!  It's right here in the words I'm giving you right now.  Look, there's also a link to the live site powered by the code in this repo!

### Wanna Contribute
Great.  Your pull request is much welcome!

Please take a look at the "Sails framework documentation" linked below though. Sails does a lot of stuff behind the scenes which might annoy you if you're not expecting it.

Here are some tips:
+ Sails automatically includes all .js and .css files from `assets/` into the project.  No need to write `<script>`!
+ Uses and auto-compiles [LESS](http://lesscss.org/) for css. See `assets/styles/importer.less` to add a new file to the project.
+ The backend is based on express.js and follows many of the same conventions.
+ Backend routes are defined in `config/routes.js`

So far, we're running bootstrap, fontawesome, jquery, and socket.io under the hood.  Feel free to stuff if it's worth the overhead.

### Links

+ [Sails framework documentation](https://sailsjs.com/documentation)
