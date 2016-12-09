## Ese - A Material Design Lite Mtaandao Theme

Ese is a Material Design Mtaandao theme(probably the first!) that uses Sass, Gulp, Bower, and of course Material Design Lite. 

#### Ese Plugins
Download free and premium plugins that add extra features and extend the functionality of Ese. 

#### Future Plans
- ~~Mtaandao customizer options~~ (v1.0.1)
- ~~add theme hooks~~ (v1.1.3)
- add custom logo support
- ship plugins with theme
- integrate other MDL components
- create portfolio page template
- create masonry blog page template

Do you have an idea? PRs welcome. 

#### For the Nerds
For customization, basic knowledge of the command line and the following dependencies are required to use Ese:

- MDL ([http://www.getmdl.io/](http://www.getmdl.io/)) 
- Node ([http://nodejs.org/](http://nodejs.org/)) -`npm install`
- Gulp ([http://gulpjs.com/](http://gulpjs.com/)) - `npm install --global gulp`
- Bower ([http://bower.io/](http://bower.io/)) -`npm install -g bower`

#### Usage
After you've downloaded Ese, and run `npm install` and `gulp` from the command line you can start using gulp.

#### Gulp

###### 1) Navigate to your new theme
`cd /your-project/mtaandao/main/themes/your-new-theme`

###### 2) Gulp tasks available:

`gulp` - Automatically handle changes to CSS, javascript, php, and image optimization. Also Livereload!

`gulp scripts` - Concatenate and minify javascript files

`gulp sass` - Compile, prefix, and minify CSS files

`gulp bower` - Install bower components

`gulp zip` - Creates a zipped file in the root of the theme. Ignores the bower_components and node_modules directories.

#### Contributors 
- [Mark Constable](https://github.com/markc) - github updater
- [Mtaandao](https://github.com/mtaandaoio) - lead developer for Ese
