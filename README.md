# [Lyrist Website](https://lyrist.app)

### Development

Add any new assets directly to the vendor folder. DO NOT REMOVE `vendor/` for any reason. Changes to `css/` are not reloaded live. If `new-age.css` needs to be edited, edit the scss files.

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

After installation, run `npm install` and then run `gulp dev` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

-   `gulp` the default task that builds everything
-   `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made to `js/`, `scss/` or `index.html`, not `css/`
-   `gulp sass` compiles SCSS files into CSS
-   `gulp minify-css` minifies the compiled CSS file
-   `gulp minify-js` minifies the themes JS file
-   `gulp copy` copies dependencies from node_modules to the vendor directory

## Copyright and License

Copyright 2013-2018 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-new-age/blob/gh-pages/LICENSE) license.
