This is an example boilerplate & folder structure for a basic self hosted Materialize installation. This means that we include the css and javascript as part of the application, rather than via CDN.

Note: init.js can be renamed to suit, and I have included several ways to initialise a single component (sidenav). The Materialize docs contain a breaking error that trips up many new users, and in any case, the initialisations they recommend are long and wasteful (redeclaration of elems each time). A much cleaner way is to use a single line without declaring a variable.
