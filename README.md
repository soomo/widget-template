# Widget Template

This set of 4 HTML pages employ the cross-domain messaging library [easyXDM](https://github.com/oyvindkinsey/easyXDM)
in order to enable communication from an external widget to the hosting product.

The four files included are as follows:

* `public/widget_wrapper.html`  
  A wrapper that is placed on the web server / domain hosting the widget.

* `public/widget.html`  
  A sample "first page" of the widget.

* `public/widget_results.html`  
  A sample "results page" of the widget, demonstrating that the conduit can be used on other pages as well.

* `public/widget_host.html`  
  A sample "host" widget page. This is the sort of code that would be placed at the widget consumer, and it can be 
  used directly (via a web server) to see the functioning of this setup.

