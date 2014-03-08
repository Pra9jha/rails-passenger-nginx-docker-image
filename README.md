rails-passenger-nginx
---------------------

This is a docker image / file you can base your rails project from. It's not really intended to be used directly or without modification.

===========

- nginx
- passenger 4.0.37
- ruby 2.1.0
- rails 4.0.0

For more versions see Dockerfile.


Getting Started
---------------

Get the image via index.docker.io

        $ docker pull networld/docker-base

        or build from source

Start a container and have a look around with:

        $ sudo docker run -t -i -p 80:80 bash -l


For more information see https://index.docker.io/u/peenuty/rails-passenger-nginx-docker-i/

