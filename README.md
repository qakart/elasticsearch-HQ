ElasticHQ
=========

Monitoring and Management Web Application for ElasticSearch instances and clusters.

Benefits:
* Active real-time monitoring of ElasticSearch clusters and nodes.
* Manage Indices, Mappings, and Nodes.
* No software to install/download. 100% web browser-based.
* Optimized to work on mobile phones, tablets, and other small screen devices.
* Easy to use and attractive user interface.
* Free (as in Beer)

Getting Started
---------------

There are several ways to use ElasticHQ. The full list and help are available here: http://www.elastichq.org/gettingstarted.html

* **FREE Hosted Version:** http://www.elastichq.org
* **Install as a Plugin:** http://www.elastichq.org/support_plugin.html
* **Download/Install Web Archive:** https://github.com/royrusso/elasticsearch-HQ/zipball/master
 
Plugin Installation
-------------------

To install as a plugin, follow these steps:
* Navigate to your /bin directory and type: ```plugin -install royrusso/elasticsearch-HQ``` 
* You should see:
```
-> Installing royrusso/elasticsearch-HQ...
Installed HQ
```
* Point your browser to ```/domain:port/_plugin/hq/```
* The cluster location url field should already be filled in with your server address. Simply hit the connect button to initiate connection.  

Requirements
------------
* A Web Browser.
* A running instance of ElasticSearch with reachable REST endpoint.

Notes + Support
------------
* Google Group can be found here: https://groups.google.com/d/forum/elastichq
* If you need sample index + documents, see here: https://github.com/royrusso/elasticsearch-sample-index
* If you find a bug, **please** create an issue and report it, or fix it and let me know. ;-)
 
License
------------
See included LICENSE.md file.
