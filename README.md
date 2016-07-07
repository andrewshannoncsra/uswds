# uswds
Bower package the the USWDS sass compiled assets.

bower register uswds git://github.com/andrewshannoncsra/uswds.git

Project created for a an 18F style technical challenge in competition for federal projects.

This package was created so we can import the uswds assets and sass compiled stylesheet to
a backbone.js/requires.js project.  The uswds scss file imports the bourbon.js framework for
mixins and so we needed to build this package in order to give bower the ability
to square all the dependencies.
