nginx_perl_enhanced
===================

This is the enhanced version of perl official module for Nginx

See official documentation here:

        http://nginx.org/en/docs/http/ngx_http_perl_module.html

The ngx_http_perl_module module is used to implement location and variable handlers in Perl and insert Perl calls into SSI.
This module is not built by default, it should be enabled with the --with-http_perl_module configuration parameter.
This module requires Perl version 5.6.1 or higher. The C compiler should be compatible with the one used to build Perl.


The enhanced version provides:
* the mean to insert additional request headers
* the mean to delete some request headers
