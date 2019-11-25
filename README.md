# Nginx &amp; Wordpress &amp; Varnish &amp; Modsecurity &amp Cloudflare

### Contents

* Nginx conf frontend for wordpress site;
* Nginx conf backend for wordpress site;
* Varnish vcls;
* Cloudflare net IPs;
* Some other staf.

### What is it?

A set of configuration files used for deploy dynamic Wordpress site with frontend <-> Varnish 5.0 <-> backend.
Frontend proxying to Varnish, varnish looking for in it's cache if Yes accelerate and return to frontend if No moved to backend.
Backend consists of two parts - sub-domain for static resources and dinamyc for other ones.
Also there are some conf files to organize Modsecurity functionality and Cloudflare protection.
