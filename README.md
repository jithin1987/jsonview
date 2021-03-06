JSONView
========

[JSONView](http://jsonview.com) is a Firefox extension that helps you view JSON documents in the browser.

Normally when encountering a [JSON](http://json.org) document (content type "application/json"), Firefox simply prompts you to download the view. With the JSONView extension, JSON documents are shown in the browser similar to how XML documents are shown. The document is formatted, highlighted, and arrays and objects can be collapsed. Even if the JSON document contains errors, JSONView will still show the raw text.

Once you've got JSONView installed, check out [this example JSON file](http://jsonview.com/example.json) to see the extension in action!

[CouchDB](http://couchdb.apache.org/) users and others who need to have "application/json" sent in the HTTP Accept header to serve JSON properly should set that option in JSONView's options panel.

If you'd like to contribute to JSONView but don't want to code, consider contributing a translation. Just go to [BabelZilla](http://www.babelzilla.org/index.php?option=com_wts&Itemid=88&type=show&extension=4898) and register as a translator for the JSONView extension. There's not much there to translate!

Reporting Issues
----------------

The code has moved over to GitHub, but the issues are still at Google Code for now: [JSONView issue tracker](http://code.google.com/p/jsonview/issues/list). Pull requests are welcome.

Building JSONView
-----------------

* Install [ant](http://ant.apache.org/)
* Run `ant` to produce an XPI

Developing JSONView
-------------------
* [Set up your Firefox addon development environment](https://developer.mozilla.org/en/Setting_up_extension_development_environment)
* Open your [Firefox profile folder](http://kb.mozillazine.org/Profile_folder)
* Create a file called `jsonview@brh.numbera.com` and put the path to your checked out JSONView's `src` folder into it.
* Run Firefox. You can now restart Firefox to pick up changes to JSONView in source.

Unofficial Ports
----------------
* [jsonview-chrome](https://github.com/jamiew/jsonview-chrome)
* [jsonview-opera](https://github.com/fearphage/jsonview-opera)



JSONView is open source software under the MIT licence.