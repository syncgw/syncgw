# ![picture logo](https://github.com/syncgw/gui-bundle/blob/master/assets/syncgw.png "sync•gw") #
 
![](https://img.shields.io/packagist/v/syncgw/syncgw.svg)
![](https://img.shields.io/packagist/l/syncgw/syncgw.svg)
![](https://img.shields.io/packagist/dt/syncgw/syncgw.svg)
 
**sync•gw** is the one and only fully portable server software available providing synchronization service between nearly any mobile device and your web server.

* Written in PHP - no binary CPU depended code.
* Support of **[XML](https://en.wikipedia.org/wiki/XML)** and 
**[WBXML](http://en.wikipedia.org/wiki/WBXML)** protocol.
* Support of **[WebDAV](https://en.wikipedia.org/wiki/WebDAV)** (**CalDAV** and **CardDAV**) protocol.
* Support of **[MicroSoft Exchange ActiveSync (EAS)](http://en.wikipedia.org/wiki/Exchange_ActiveSync)** protocol (2.5, 12.0, 12.1, 14.0, 14.1, 16.0, 16.1).
* Only a web server with PHP is required to run **sync•gw** (no additional software or tools required).
* Full internationalization support.
* Multi byte support (support for e.g. Japanese language).
* Support for time zones..
* Multiple level of logging supported
* Intelligent field assignment - calculated based on mix of configuration file and probability calculation.
* Programming documentation available (see **Developers Guide** in the [Downloads](../doc-bundle/Downloads.md).
* Support for encrypted message exchange using SSL web server setting.
* Administrator browser interface with password protection.
* Contact synchronization support.
* Calendar and task synchronization support.
* Notes synchronization support.
* Experimental: Mail synchronization support.

**sync•gw** setup is very easy. Install this project, define a administrator password, connect a data base handler and **sync•gw** is ready for your first synchronization.

A detailed description of available configuration option is available in our browser interface documentation available in the [here](../doc-bundle/Downloads.md)).

## Installation ##

If you want to use **sync•gw** go to your base directory on your web server and enter

```bash
composer create-project syncgw/syncgw .
```
(Don't forget the "." at the end of the command line).

Then start **sync•gw** by typing into your browser's URL bar `http://[your-domain.tld]/[path to application directory]/sync.php`.

At least select "Configure **sync•gw**" and check your settings and click on "Save".

## License ##
This plugin is released under the [GNU General Public License v3.0](https://github.com/toteph42/syncgw/blob/master/syncgw/LICENSE).

|  <a href="https://www.paypal.com/donate/?hosted_button_id=DS6VK49NAFHEQ" target="_blank" rel="noopener">   <img src="https://www.paypalobjects.com/en_US/DK/i/btn/btn_donateCC_LG.gif" alt="Donate with PayPal"/> </a> | 
| --- | 

[[Documentation](https://github.com/syncgw/doc-bundle/blob/master/README.md)]
[[System requirements](https://github.com/syncgw/doc-bundle/blob/master/PreReqs.md)] 
[[Available bundles](https://github.com/syncgw/doc-bundle/blob/master/Packages.md)] 
[[List of all changes](https://github.com/syncgw/doc-bundle/blob/master/Changes.md)] 
[[Additional Downloads](https://github.com/syncgw/doc-bundle/blob/master/Downloads.md)] 
[[Frequently asked questions](https://github.com/syncgw/doc-bundle/blob/master/FAQ.md)] 
