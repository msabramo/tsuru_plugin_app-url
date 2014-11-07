tsuru_plugin_app-url
====================

Simple [tsuru
plugin](http://docs.tsuru.io/en/latest/using/cli/plugins.html) to
display just the app's tsuru web URL and nothing else

Example usage:

    $ tsuru app-url -a my-cool-app
    http://my-cool-app.10.128.40.70.xip.io

    $ cd my-cool-app
    $ tsuru app-url
    http://my-cool-app.10.128.40.70.xip.io
