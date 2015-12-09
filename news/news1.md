# News 1
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum mattis finibus dolor, vel consectetur orci elementum non. Nam vitae suscipit tortor. Nullam libero ipsum, interdum vel lacus quis, condimentum pellentesque nisl. Etiam lobortis ante libero, a posuere dolor efficitur et. Etiam id volutpat metus. Cras tincidunt placerat efficitur. Duis eu mollis tortor. In vitae elit et turpis pharetra aliquam semper sed nibh. Phasellus ornare justo libero, molestie mollis nisl luctus vitae. Ut sit amet aliquet justo, nec aliquam nisi. Duis gravida ut purus fermentum porttitor. Vestibulum eleifend tellus nec ullamcorper sodales. Duis at nisi id nibh varius suscipit vel sit amet elit. In consequat, felis ac malesuada suscipit, elit dolor porttitor risus, vitae tincidunt ligula dolor at enim.
  - Type some Markdown on the left
  - See HTML in the right
  - Magic

Donec vitae venenatis enim. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Morbi nec tellus egestas, vehicula risus vel, interdum augue. Morbi leo dolor, blandit vitae malesuada vitae, pharetra efficitur erat. Curabitur congue ex aliquam risus consectetur tincidunt. Duis faucibus neque vitae velit bibendum, ultrices tempus erat tincidunt. Donec tortor sapien, scelerisque sit amet congue nec, varius sed dui. Nunc quis pretium lacus. Nullam at rhoncus quam. Quisque arcu purus, ultricies sollicitudin lorem ac, tincidunt consectetur libero.

Sed et egestas mi. Nunc sagittis pharetra ante consequat scelerisque. Aliquam aliquet sem eleifend enim cursus suscipit. Fusce tincidunt ac dui ut mollis. Integer vestibulum iaculis laoreet. Aliquam porttitor lorem eros, quis tincidunt sem posuere sit amet. In efficitur fermentum nibh. Proin volutpat rutrum consectetur. Curabitur ac interdum elit. Duis suscipit venenatis ipsum. Donec varius tortor eu vestibulum lacinia. Aenean commodo metus a quam efficitur, sed tempor quam rutrum. Curabitur fermentum vitae eros at dictum. Nam porttitor gravida neque. Quisque in metus nisl. As [John Gruber] writes on the [Markdown site][df1]

Some quotes:
> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually* written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.

### Version
3.2.0

### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Ace Editor] - awesome web-based text editor
* [Marked] - a super fast port of Markdown to JavaScript
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Gulp] - the streaming build system
* [keymaster.js] - awesome keyboard handler lib by [@thomasfuchs]
* [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

### Installation

You need Gulp installed globally:

```sh
$ npm i -g gulp
```

```sh
$ git clone [git-repo-url] dillinger
$ cd dillinger
$ npm i -d
$ mkdir -p downloads/files/{md,html,pdf}
$ gulp build --prod
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins

* Dropbox
* Github
* Google Drive
* OneDrive

Readmes, how to use them in your own application can be found here:

* [plugins/dropbox/README.md] [PlDb]
* [plugins/github/README.md] [PlGh]
* [plugins/googledrive/README.md] [PlGd]
* [plugins/onedrive/README.md] [PlOd]

### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma start
```

### Todos

 - Write Tests
 - Rethink Github Save
 - Add Code Comments
 - Add Night Mode

License
----

MIT


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [@thomasfuchs]: <http://twitter.com/thomasfuchs>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [marked]: <https://github.com/chjj/marked>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [keymaster.js]: <https://github.com/madrobby/keymaster>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>
   
   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]:  <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>


