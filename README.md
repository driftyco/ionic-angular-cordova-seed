ionic-angular-cordova-seed
==========================

The perfect starting point for an Ionic project.

## Quick Start

Before getting started, make sure that you've installed Bower, and Sass.

```bash
$ sudo npm install -g bower
$ sudo gem install sass
```

After checking on that, start using the seed project by downloading or cloning the seed project, and opening the directory it downloaded or extracted to.

```bash
$ git clone https://github.com/driftyco/ionic-angular-cordova-seed.git
$ cd ionic-angular-cordova-seed
```

The seed project comes with a standard Cordova directory structure. All of the files that you'll be working with are in the ```www/``` directory. Inside the directory, you'll need to first install Ionic with Bower.

```bash
$ cd www
$ bower install
```

When that's done, you'll notice a new directory called ```bower_components```. This keeps all of the Ionic files managed neatly, making it quick and easy to update Ionic when a new release comes out. Learn more about Bower on their website, [bower.io](http://bower.io/).

You'll also see that the app's main css file, ```css/app.css```, is very long. Luckily, because the seed project uses Sass (check out their website, [sass-lang.com](http://sass-lang.com/)) for CSS preprocessing, you won't need to poke around in this file much at all. All the work that you do will be in the ```scss/``` directory. After looking at ```scss/app.scss```, build the css by running:

```bash
$ sass --watch scss:css
```

That's just about everything. You can preview the app either in the browser or on the iOS Simulator.

To open the app in the browser, run:

```bash
$ python -m SimpleHTTPServer 8000
$ open http://localhost:8000/
```

To open the app in the iOS Simulator, make sure that you have both the XCode Developer Tools and Cordova installed, and then run:

```bash
$ cordova platform add ios
$ cordova run ios
```

## Learn More

- [Ionic Tutorials](http://ionicframework.com/tutorials/)
- [Ionic Documentation](http://ionicframework.com/docs/)
- [Ionic Forum](http://forum.ionicframework.com/)
