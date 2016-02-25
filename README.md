CakePHP Goo.gl Plugin
===================

Plugin for shorten url easy mode in cakephp.

Requirements
------------

* CakePHP 2.+

Documentation
-------------

* Load plugin in bootstrap.php;
* On your Controller load de component:
<code>
	public $components = array(
        "Googl.Googl"
    );
</code>

* For using: ``$this->Googl->shorten($url); ``

License
-------

Copyright 2016. All rights reserved.

Licensed under the [MIT](http://www.opensource.org/licenses/mit-license.php) License. Redistributions of the source code included in this repository must retain the copyright notice found in each file.
