#How the internet works

A brief work in progress description of how the internet works.

![](http://i.imgur.com/PNC6GhF.png)
[image source](http://www.tomshardware.com/news/internet-browser-vlad-Gerasimo-comic-strip,11598.html)

##The Characters:

**The User** - Often found perusing cat videos.

**The Browser** - A swift runner, he goes all around the internet collecting information for the User.

##The Story:

###Act 1:
####Scene 1:
1. The **user** types the URL (Universal Resource Locator) into the **browser**.
####Scene 2:
2. The **browser** parses the URL.
  * URLs are formatted like this:
    `<protocol>://<server>/<path>`
####Scene 3:
3. The **browser** looks up `<server>` via the DNS (Domain Name System)

###Act 2:
####Scene 1:
4. The DNS responds with an ip address
####Scene 2:
5. Your **browser** connects to this ip address
####Scene 3:
6. Your **browser** sends a HTTP request for that `<path>`

###Act 3:
####Scene 1:
7. The server at that ip address sends you the file(s) at that path.
####Scene 2:
8. Your **browser** displays those files using it's ability to read html, css, and javascript.
####Scene 3:
8. Your **browser** end your connection with the server
