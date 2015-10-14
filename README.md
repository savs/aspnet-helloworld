ASPNET Hello World with Docker on a Mac
---------------------------------------

This sample provides a basic working hello world for Docker users.

Usage
-----

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