## Bootstrap4 Starter Project

This is a bootstrap4 Starter Project. Iused [NPM](https://www.npmjs.com/) to manage all the packages that the project uses. As you can see in the `package.json`, the main dependencies are:

* [Bootstrap](https://getbootstrap.com/)
* [Font-awesome](https://fontawesome.com/)
* [JQuery](https://jquery.com/)
* [Popper.js](https://popper.js.org/)
* [Browser-sync](https://browsersync.io/)

I also used [Gulp](https://gulpjs.com/) to automate some tasks. They can be found in the `gulpfile.js` file.

First, you need install all the dependencies by running:
```
$npm install
```

Next, you can run:

```
$gulp
```
This command executes the defined tasks, including serving the project in the browser.

Note that we got the same result by running:

```
$npm start
```

#### Why?

You can notice that in the `package.json`, i defined `gulp` in the **scripts** tag. This object is used to define all the scripts that you may want to run when starting your project.
