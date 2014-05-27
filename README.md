DOMwriter [![Code Climate](https://codeclimate.com/github/federico-lox/DOMwriter.png)][codeclimate]
=========

DOMwriter binds document.write calls to an HTMLElement to preserve the content
of the page after the DOM has already been processed while maintaining the
original behaviour of the native function.

Just as an example, this allows for lazy-loading 3rd party code such as that served
by Ad networks (document.write is still an industry standard in that area).

More information (and docs) coming soon.

Credits
-------

*	[Federico "Lox" Lucignano](https://plus.google.com/117046182016070432246 "Google profile"), creator and mantainer
*	All the [contributors](http://github.com/federico-lox/DOMwriter/contributors "DOMwriter contributors at GitHub")


[codeclimate]: https://codeclimate.com/github/federico-lox/DOMwriter
