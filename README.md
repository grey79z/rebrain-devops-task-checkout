# Nginx Configuration File

This directory contains default nginx configuration file.
___
## Configuration File’s Structure

Nginx consists of modules which are controlled by directives specified in the configuration file. Directives are divided into simple directives and block directives. A simple directive consists of the name and parameters separated by spaces and ends with a semicolon `;`. A block directive has the same structure as a simple directive, but instead of the semicolon it ends with a set of additional instructions surrounded by braces `( {` and `} )`. If a block directive can have other directives inside braces, it is called a context (examples: [events](http://nginx.org/en/docs/ngx_core_module.html#events), [http](http://nginx.org/en/docs/http/ngx_http_core_module.html#http), [server](http://nginx.org/en/docs/http/ngx_http_core_module.html#server), and [location](http://nginx.org/en/docs/http/ngx_http_core_module.html#location)).

Directives placed in the configuration file outside of any contexts are considered to be in the [main](http://nginx.org/en/docs/ngx_core_module.html) context. The *events* and *http* directives reside in the *main* context, *server* in *http*, and *location* in *server*.

The rest of a line after the `#` sign is considered a comment.

## Useful Links

- [Official Nginx Webpage](http://nginx.org/)
- [Nginx Beginners Guide](http://nginx.org/en/docs/beginners_guide.html)
- [Nginx Changelog](http://hg.nginx.org/nginx/)

## Contact Me
Please feel free to contact me via grey79z@mail.ru.  
My [gitlab profile](https://gitlab.rebrainme.com/grey79z).