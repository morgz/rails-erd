Rails ERD - Generate Entity-Relationship Diagrams for Rails applications
========================================================================

[Rails ERD](http://rails-erd.rubyforge.org/) is a Rails plugin that allows
you to easily generate a diagram based on your Active Record models. The
diagram gives an overview of how your models are related. Having a diagram
that describes your models is perfect documentation for your application.

The second goal of Rails ERD is to provide you with a tool to inspect your
application's domain model. If you don't like the default output, it is very
easy to use the API to build your own diagrams.

Rails ERD was created specifically for Rails 3. It uses Active Record's
built-in reflection capabilities to figure out how your models are associated.


Preview
-------

Here's an example entity-relationship diagram that was generated by Rails ERD:

![Entity-Relationship Diagram](http://rails-erd.rubyforge.org/images/entity-relationship-diagram.png)

Browse the [gallery](http://rails-erd.rubyforge.org/gallery.html) for more
example diagrams.


Getting started
---------------

See the [installation instructions](http://rails-erd.rubyforge.org/install.html)
for a complete description of how to install Rails ERD. Here's a summary:

* Install Graphviz 2.22+ ([how?](http://rails-erd.rubyforge.org/install.html))

* Add <tt>gem "rails-erd"</tt> to your application's Gemfile

* Run <tt>bundle exec erd</tt>


Learn more
----------

More information can be found on [Rails ERD's project homepage](http://rails-erd.rubyforge.org/).

If you wish to extend or customise Rails ERD, take a look at the [API documentation](http://rails-erd.rubyforge.org/doc/).


About Rails ERD
---------------

Rails ERD was created by Rolf Timmermans (r.timmermans *at* voormedia.com)

Copyright 2010-2013 Voormedia - [www.voormedia.com](http://www.voormedia.com/)


License
-------

Rails ERD is released under the MIT license.
