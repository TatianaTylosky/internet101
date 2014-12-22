#How the internet works

A brief work in progress description of how the internet works.

![](http://i.imgur.com/PNC6GhF.png)
[source](http://www.tomshardware.com/news/internet-browser-vlad-Gerasimo-comic-strip,11598.html)

##The characters:

**The User** - Often found perusing cat videos.

**The Browser** - A swift runner, he goes all around the internet collecting information for the User.

##Acts:

1. The **user** types the URL (Universal Resource Locator) into the *browser*.
2. The **browser** parses the URL.
  * URLs are formatted like this:
    `<protocol>://<server>/<path>`
3. The **browser** looks up `<server>` via the DNS (Domain Name System)
4. The DNS responds with an ip address
5. Your **browser** connects to this ip address
6. Your **browser** sends a HTTP request for that `<path>`
7. The server at that ip address sends you the file(s) at that path.
8. Your **browser** displays those files using it's ability to read html, css, and javascript.
8. Your **browser** end your connection with the server
