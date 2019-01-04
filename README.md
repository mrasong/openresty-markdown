## openresty markdown to html

 - openresty
 - marked.js
 - body_filter_by_lua_block


### usage

 1. push `enable-markdown.conf` `rewrite/markdown.conf` to your openresty conf dir, 
 the default path may be `/usr/local/openresty/nginx/conf`
 2. open your `nginx.conf` file, add an including for your markdown server.
 Here is an example for you `example.conf`
 3. `openresty -s reload`