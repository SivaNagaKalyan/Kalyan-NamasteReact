# Q1.Why react is known as "React"?
React was developed for applications that have constantly changing data. Since React is a front-end framework or the “View” in MVC, this means that as the user clicks around and changes the app's data, the view should “react” or change with those user events.

# Q2.What is Emmet?
Emmet is a plug in for many popular text editors which greatly improves HTML & CSS workflow,
and Emmet does fulfill what they promise, you can use short expressions to generate HTML markup, CSS

# Q3.What is CDN?
A content delivery network (CDN) is a group of geographically distributed servers that speed up the delivery of web content by bringing it closer to where users are. Data centers across the globe use caching, a process that temporarily stores copies of files, so that you can access internet content from a web-enabled device or browser more quickly through a server near you. CDNs cache content like web pages, images, and video in proxy servers near to your physical location. This allows you to do things like watch a movie, download software, check your bank balance, post on social media, or make purchases, without having to wait for content to load.

# Q4.  What is cross origin?
The purpose of crossorigin attribute is used to share the resources from one domain to another domain
The crossorigin attribute sets the mode of the request to an HTTP CORS Request.
Web pages often make requests to load resources on other servers. Here is where CORS comes in.
A cross-origin request is a request for a resource (e.g. style sheets, iframes, images, fonts, or scripts) from another domain.CORS is used to manage cross-origin requests.

# Q5. Difference between production build and development build?
The development build is used - as the name suggests - for development reasons. You have Source Maps, debugging and often times hot reloading ability in those builds.
The production build, on the other hand, runs in production mode which means this is the code running on your client's machine. The production build runs uglify and builds your source files into one or multiple minimized files.
# Async and Defer?
Both async and defer have one common thing: downloading of such scripts doesn’t block page rendering. So the user can read page content and get acquainted with the page immediately.
But there are also essential differences between them:

async is Load-first order. Their document order doesn’t matter which loads first runs first. DOM content loaded is	Irrelevant. May load and execute while the document has not yet been fully downloaded. That happens if scripts are small or cached, and the document is long enough.
defer is Document order (as they go in the document).Execute after the document is loaded and parsed (they wait if needed), right before DOMContentLoaded.