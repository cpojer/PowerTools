MooTools PowerTools!
====================

PowerTools! for MooTools brings powerful low-level Plugins to speed up the development of JavaScript-heavy web applications.

Download, Build and Demos
----------------

* [Demos and Build](http://cpojer.net/PowerTools)

Download

	git clone git://github.com/cpojer/PowerTools.git
	cd PowerTools
	./update


Included Components
-------------------

* [Custom-Event](https://github.com/cpojer/mootools-custom-event)
* [Mobile](https://github.com/cpojer/mootools-mobile)
* [Class-Extras](https://github.com/cpojer/mootools-class-extras)
* [History](https://github.com/cpojer/mootools-history)
* [DynamicMatcher](https://github.com/cpojer/mootools-dynamic-matcher)
* [Form-Placeholder](https://github.com/cpojer/mootools-form-placeholder)
* [Form-AutoGrow](https://github.com/cpojer/mootools-form-autogrow)
* [Event-Stack](https://github.com/cpojer/event-stack)
* [Scroll-Loader](https://github.com/cpojer/scroll-loader)
* [Tree](https://github.com/cpojer/mootools-tree)
* [Interface](https://github.com/cpojer/mootools-interface)

Build
-----

Build via [Packager](http://github.com/kamicane/packager). Requires packager to be globally available.

	./register
	./build > powertools.js

This builds all of PowerTools! and puts the contents into 'powertools.js'. Alternatively you can also ./register all parts of PowerTools! and then build them manually. For more information on this see the repositories of each component.

Update all repositories

	./update <remote>

Where <remote> is the name of the git remote, defaults to 'origin'.

Credits
-------

Thanks to [@timwienk](https://github.com/timwienk) for helping me with the bash scripts.
