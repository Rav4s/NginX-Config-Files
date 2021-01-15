# NginX-Config-Files
Some config files for the NginX web server &amp; reverse proxy server. These files are used in the YouTube video at https://youtu.be/qdq02d64pxc and the blog post at https://www.yeetpc.com/blog/nginx-reverse-proxy/.
## reverse-proxy.conf
This file contains a config for the www subdomain and the non-www subdomain (For example, www.yeetpc.com and yeetpc.com). The config file handles redirecting http to https, redirecting non-www to www, encrypting connections with SSL, and proxying to a backend server.
## subdomain-proxy.conf
This file contains a config for any other subdomain on your site (provided that you have a CNAME record for it). It handles redirecting http to https, encrypting connections with SSL, and proxying to a backend server.
