# Tangelo: Rapidly create powerfully visual web applications.

**Tangelo** is a web framework built on top of
[CherryPy](http://www.cherrypy.org/) for producing rich web applications
that pair your data with cutting-edge visual interfaces.

In a nutshell, Tangelo is a flexible HTML5 web server architecture that cleanly separates
your web *applications* (pure Javascript, HTML, and CSS) and web *services*
(pure Python), bundled with some great tools to get you started. Mix and match
from the following to create your own breed:

* [Bootstrap](http://twitter.github.com/bootstrap/) to put your app's style on a solid
footing.
* [D3](http://d3js.org) for constructing all manner of dynamic and animated charts.
* *Vega*, a brand new declarative language for defining visual interfaces.
* [MongoDB](http://www.mongodb.org) for a flexible, speedy NoSQL backend to feed
data to your apps.
* *tangelo.js*, a set of tools and interface elements that make it easy to create
apps that put your data front and center.

# Installation

Installation is simple -- just install a few dependencies, clone this repository,
build the system, and run the `tangelo start` command. Then, point your
browser to [http://localhost:8080](http://localhost:8080) to check things out.

See the [Installation](http://github.com/Kitware/tangelo/wiki/Installation) page on
the wiki for detailed instructions.

# System Architecture

Tangelo applications are divided into two functional layers: the *frontend*
and *backend*, with [Ajax](http://en.wikipedia.org/wiki/Ajax\_(programming\))
bridging the gap between them.

The *frontend* is a standard website -- HTML for content and formatting, with
CSS for styling and JavaScript for dynamic behavior.  The JavaScript code can
also make Ajax calls to the Python *backend* modules to request various
services, such as database access, server side processing, or anything else that
you can imagine.

See the [Application Architecture](http://github.com/Kitware/tangelo/wiki/Architecture) page
on the wiki for more information.

# Get Involved

Fork our repository and do great things. At [Kitware](http://www.kitware.com),
we've been contributing to open-source software for 15 years and counting, and
want to make Tangelo as useful to as many as possible.
