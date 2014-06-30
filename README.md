# Ruby on Rails Tutorial: sample application

This is the sample application for
the [*Ruby on Rails Tutorial*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

== README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.


========

# Welcome to Nitrous.IO

Nitrous.IO enables you to develop web applications completely in the
cloud. This development "box" helps you write software, collaborate
real-time with friends, show off apps to teammates or clients, and
deploy apps to production hosting sites like Heroku or Google App
Engine.

## Getting Started

This box is a fully functional Linux environment in which you can
develop any Linux-based application. This box comes bundled with gcc,
make, perl and other system-level libraries, enough to get you started
on your application development journey.


## Setting up your SSH Keys

We recommend that you use Github (www.github.com) to manage your
application's code. To interact with your code on Github, you'll need to
add your Nitrous.IO box's SSH keys to Github.  Follow these steps to get
started:

http://help.nitrous.io/github-add-key/

## Installing Databases

Your box comes installed with Autoparts, with which you can install
databases such as MySQL, Redis, Postgres, Memcache and many others.
Look for the "Autoparts" menu in the IDE, or read more here:

http://help.nitrous.io/autoparts/

## Previewing your application

Once you're running a webserver, keep an eye on the port where your
server is running.  Then click the "Preview" menu title in the IDE above
and select the port where your application is running. For more
information, check out this help article:

http://help.nitrous.io/preview/

## Real-Time Collaboration

You can invite friends and teammates into this web IDE session so you
can code collaboratively on the same codebase.  This can be really
helpful when giving tutorials, troubleshooting some code, or just doing
some pair programming.  Click the "Collaborate" menu and then manage
collaborators.

http://help.nitrous.io/collab/

## Deployment

Once you've built your application, you can deploy to various
cloud services such as Heroku, Google App Engine, Nodejitsu, Azure and
others.  You can read more about it here:

http://help.nitrous.io/categories/deployment/

## Ruby / Rails

Ruby is installed via [Autoparts](http://help.nitrous.io/autoparts/) and can be
managed with [chruby](https://github.com/postmodern/chruby). You can install
additional Ruby versions using Autoparts.

For example, to install Ruby 2.0:

  parts install ruby2.0

To use a specific Ruby version, create a .ruby-version file:

  echo 'ruby-2.1' > .ruby-version

This Ruby box also comes with Node.JS installed via Autoparts.
