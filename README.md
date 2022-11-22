# php-httpd
Basic php code with httpd (Apache) webservice in docker

## Goal Of This Project
The goal of this container image is to provide an example for running simple PHP with Httpd/Apache webserver in a container which follows the best practices and is easy to understand and modify to your needs.

## How to Use?
First of all, Clone all the PHP container from https://github.com/nayakasbl/php-httpd
<pre><code>gh repo clone nayakasbl/php-httpd</code></pre>
Build the images with command bellow and do not forget to add the directory of the repository that you have cloned before.
<pre><code>docker build -t php-httpd:latest (directory)</code></pre>
Then run the docker images which you have cloned before. You can modify 2020 as a port of PHP container. 
<pre><code>docker run -p 2020:80 php-httpd:latest </code></pre>
After that, see the output or the result on http://localhost:2020. 

Now you have the simple PHP running container!! 
