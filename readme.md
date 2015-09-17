# jQuery: Pseudo

Dynamically update CSS attributes of pseudo elements.

This plugin was created from a need to update pseudo elements in fluid ways that could not be addressed by individual classes.

Such use cases may be:
* responding to user input (mouse, touch etc.),
* animating based on variables and
* using attr() values in other attributes other than content.

Since JavaScript can't manipulate these elements directly, as they are not considered "real" elements, there is little to no support for such functionality. This may change in the future...


## Examples

* [Follow Mouse](http://rawgit.com/makesites/jquery-pseudo/master/examples/example-01.html)
* [Ripple effect](http://rawgit.com/makesites/jquery-pseudo/master/examples/example-02.html)


## Install

Install plugin after jQuery and you should be good to go.


## Usage

Example:
```
$el.pseudo("after","margin-top",axis.y +"px");
```


## Options

Currently there are no parameters for this plugin


## Credits

Initiated by Makis Tracend ( [@tracend](http://tracend.me/) )

Distributed by [Makesites.org](http://makesites.org)

### Thanks

Inspired by a [micro-lib](http://mcgivery.com/htmlelement-pseudostyle-settingmodifying-before-and-after-in-javascript/) of Andrew McGivery

### License

Released under the [MIT license](http://makesites.org/licenses/MIT)
