# shibboleth-fastcgi
shibboleth for use with fastcgi, using supervisor as the controlling daemon

Most of the inspiration for this docker image came from installing [dspace with nginx and shibboleth](https://github.com/ufal/clarin-dspace/wiki/Using-Nginx).

The fastcgi shibboleth unix socket connections are located at

/run/shibboleth/shibauthorizer.sock
/run/shibboleth/shibresponder.sock

Look at /etc/supervisor/conf.d/shibboleth.conf for more details.
