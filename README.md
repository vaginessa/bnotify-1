
[![bnotify](http://i.imgur.com/GDWvTpp.png)](#)

# `$ bnotify`

 [![Support me on Patreon][badge_patreon]][patreon] [![Buy me a book][badge_amazon]][amazon] [![PayPal][badge_paypal_donate]][paypal-donations] [![Version](https://img.shields.io/npm/v/bnotify.svg)](https://www.npmjs.com/package/bnotify) [![Downloads](https://img.shields.io/npm/dt/bnotify.svg)](https://www.npmjs.com/package/bnotify)

> A notification system written in NodeJS using the BAT platform.

## :cloud: Installation

You can install the package globally and use it as command line tool:


```sh
$ npm i -g bnotify
```


Then, run `bnotify --help` and see what the CLI tool can do.


```
$ bnotify --help
Usage: bnotify <title> <description> <duration> <icon>
```


Ensure you have [installed](https://github.com/IonicaBizau/dotfiles#applications) and [configured NodeJS and NPM](https://github.com/IonicaBizau/dotfiles#npm-config).


Ensure you have installed the [BAT](https://github.com/IonicaBizau/bat#installation) on your machine.

## Screenshots
```sh
$ bnotify 'Hello World' 'I am BNotify' 10000
```
![](http://i.imgur.com/kzaJa58.png)

### Multiple notifications
![](http://i.imgur.com/nnHdnDu.png)

### Multiple notifications
![](http://i.imgur.com/nnHdnDu.png)


## :clipboard: Example


Here is an example how to use this package as library. To install it locally, as library, you can do that using `npm`:

```sh
$ npm i --save bnotify
```



```js
// Dependencies
var BNotify = require("bnotify");

// Show the notification
BNotify({
    title: "Test Notification"
  , description: "Adipisicing molestias soluta consectetur debitis doloribus. Doloremque amet temporibus suscipit quis ipsum vitae rerum ad iure nulla repellat iure molestias. Provident reiciendis veritatis doloribus maxime eum repellendus aut possimus ab!"
  , duration: 4000
  , icon: "/bell.png"
}, function () {
    process.exit(0);
});
```

## :question: Get Help

There are few ways to get help:

 1. Please [post questions on Stack Overflow](https://stackoverflow.com/questions/ask). You can open issues with questions, as long you add a link to your Stack Overflow question.
 2. For bug reports and feature requests, open issues. :bug:
 3. For direct and quick help from me, you can [use Codementor](https://www.codementor.io/johnnyb). :rocket:


## :memo: Documentation

For full API reference, see the [DOCUMENTATION.md][docs] file.

## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :sparkling_heart: Support my projects

I open-source almost everything I can, and I try to reply everyone needing help using these projects. Obviously,
this takes time. You can integrate and use these projects in your applications *for free*! You can even change the source code and redistribute (even resell it).

However, if you get some profit from this or just want to encourage me to continue creating stuff, there are few ways you can do it:

 - Starring and sharing the projects you like :rocket:
 - [![PayPal][badge_paypal]][paypal-donations]—You can make one-time donations via PayPal. I'll probably buy a ~~coffee~~ tea. :tea:
 - [![Support me on Patreon][badge_patreon]][patreon]—Set up a recurring monthly donation and you will get interesting news about what I'm doing (things that I don't share with everyone).
 - **Bitcoin**—You can send me bitcoins at this address (or scanning the code below): `1P9BRsmazNQcuyTxEqveUsnf5CERdq35V6`

    ![](https://i.imgur.com/z6OQI95.png)

Thanks! :heart:



## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[badge_patreon]: http://ionicabizau.github.io/badges/patreon.svg
[badge_amazon]: http://ionicabizau.github.io/badges/amazon.svg
[badge_paypal]: http://ionicabizau.github.io/badges/paypal.svg
[badge_paypal_donate]: http://ionicabizau.github.io/badges/paypal_donate.svg
[patreon]: https://www.patreon.com/ionicabizau
[amazon]: http://amzn.eu/hRo9sIZ
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(https%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: https://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
