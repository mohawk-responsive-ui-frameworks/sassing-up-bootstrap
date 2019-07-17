# Sassing Up Bootstrap

In this activity we will be learning how to utilize Sass in a Bootstrap project. Bootstrap's styles are written with Sass and allows you to utilize said Sass files to take advantage of variables, maps, mixins, and more. Throughout this activity you will be introduced to the major advantages of pairing Sass with Bootstrap. In order to utilize its Sass files they must either be downloaded or installed as an [_npm package_](https://www.npmjs.com/) which we'll delve into in a later module. In the meantime all npm packages will be installed and pre-configured for you.

***
- [Applying Bootstrap](#applying-bootstrap)
- [Resources](#resources)
***




## Applying Bootstrap

If we start this repositories web server and view its home page you'll find something that looks like this:

***
![Initial page](.readme-assets/initial-page.png)
***

The HTML and all custom CSS are loaded for this page however Bootstrap's CSS isn't loaded. Previously we included a `bootstrap.css` file on all of our webpages but we're going to in this activity include it as an npm package via Sass. npm packages live in the `node_modules` folder that appears whenever we initially run `npm install` on a newly cloned repository. If we reference [this section](https://getbootstrap.com/docs/4.3/getting-started/theming/#file-structure) of Bootstrap's documentation, what you find within your `node_modules` folder should match what's documented.

In the [next section](https://getbootstrap.com/docs/4.3/getting-started/theming/#importing) of the documentation we can see how we can use Sass's `@import` feature we learned about in the previous module. Go ahead and include all of Bootstrap <small>(Option A)</small>. When complete the top of your page should look like this:

***
![webpage after bootstrap is imported](.readme-assets/import-bootstrap.png)
***

If we really wanted to do all we could to reduce the payload of our webpage, we could include only the parts of Bootstrap we need as seen in "Option B". Bootstrap in it's entirety only consumes 20KB of bandwidth when sent to the web browser so it's generally not worth the development time and added development complexity to manage which pieces of Bootstrap to selectively include onto your webpage but in extreme cases can be useful.




## Resources

- [**Docs:** Theming](https://getbootstrap.com/docs/4.3/getting-started/theming/)
