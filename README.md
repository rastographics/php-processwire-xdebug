# php-processwire-xdebug
Adds Xdebug to the [alphine-php-processwire](https://github.com/gebeer/alpine-php-processwire) image

When spinning up a container with this image, use the ARG `docker_hostip` to specify the (non-docker-network) IP Address of the host computer so Xdebug can communicate.
