_This TODO list is mostly based on the input from Rubén Romero. Thanks!_

* The user should be able to change the refresh time
* Show description for each metric
* A counter of how much time the dashboard has been running
* Show metrics for HTTP return codes: 200, 404, 5xx -> This info comes from the log
* Show metrics for each Backend
* Show metrics for each Director
* A way to select diferent Varnish Agent if we have more than one Varnish Cache
* A way to auto-discover Varnish Agent on the network (should be a patch to VA2)

Ideas and examples:
* HA Proxy: http://demo.1wt.eu/
* Apache mod_status: http://www.cyberciti.biz/faq/apache-server-status/
* Lighttpd server status: http://www.freakcode.com/projects/pretty-lighty-status-page
* Varnish Status: https://github.com/huayra/libvmod-status
* Ideas from Varnish (pages 15 - 18): https://www.varnish-cache.org/sites/default/files/VUG5%20-%20Introductions_0.pdf

If you have any other idea, please fork and make a pull request, or send me an email.
