ASPNET Hello World with Docker on a Mac
---------------------------------------

This sample provides a basic working hello world for Docker users.

Usage
-----

This image is on [Docker Hub](https://hub.docker.com/r/savs/aspnet-helloworld/) for easier usage.

    docker run -t -d -p 5004:5004 savs/aspnet-helloworld

Then open your browser and point it to your [Docker host IP](http://stackoverflow.com/a/17158003) on port 5004.

Build your own
--------------

Do the following:

    git clone https://github.com/savs/aspnet-helloworld.git
    cd aspnet-helloworld
    docker build -t helloworld .
    docker run -t -d -p 5004:5004 webapp

References
----------

* http://blog.tonysneed.com/2015/05/25/develop-and-deploy-asp-net-5-apps-to-docker-on-linux/
* https://github.com/aspnet/Home/tree/dev/samples/latest/HelloWeb
* http://blog.markrendle.net/fun-with-asp-net-5-linux-docker-part-3/