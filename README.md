AngularJS Template
==================

Basic template with my personal setup for angularJS based single page applications

What's included
---------------

- Yeoman generated layout
- Grunt tasks
- Karma test runner
- Bower package manager and configured dependencies such as:
    - LESS
    - Twitter Bootstrap LESS
    - AngularJS
    - AngularJS LocalStorageService plugin
    - AngularJS HTTP-Auth (my fork)
    - JS Hashes
    - Underscore JS

Requirements
------------

- NodeJS with npm
- Yeoman (scaffolding)
- Karma (test runner)
- PhantomJS (headless brower for testing - can be replaced changing the karma configuration in Gruntfile.js)

To get started
--------------

Run these commands:

    git clone git@github.com:Astrac/angular-tpl.git my-project
    cd my-project
    npm install
    bower install
    grunt server

Some useful tasks:

- **grunt server**        Starts the grunt development server with livereload
- **grunt test**          Runs the test suite
- **grunt test-watch**    Starts the karma server in auto-run mode
- **grunt build**         Builds a dist package

