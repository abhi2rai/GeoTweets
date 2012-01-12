This Git repository includes all of the source code used in the [GeoTweets screencast][tutorial].

The tutorial includes several checkpoints:

* [skeleton][00] - From scratch: creating a skeleton for the app
* [gui][01] - Building the Graphical User Interface (GUI)
* [static][02] - Creating a template for the Twitter timeline
* [dynamic][03] - Fetching data from the Twitter API
* [map][04] - Adding a map with markers for geotagged tweets

Using this repository to follow the screencast
----------------------------------------------

First, you'll have to clone this repository:

    git clone git://github.com/senchalearn/GeoTweets.git

Change into the directory:

    cd GeoTweets

By default, the `git clone` command will only create the master branch locally. If you want to study the code at each checkpoint, you will have to fetch each of the other branches. You can do so by running the following:

    git checkout -b 00_skeleton origin/00_skeleton
    git checkout -b 01_gui origin/01_gui
    git checkout -b 02_static origin/02_static
    git checkout -b 03_dynamic origin/03_dynamic
    git checkout -b 04_map origin/04_map

You can review the list of local branches by running:

    git branches

And you can switch between branches with the `checkout` command. For example, to check out the `04_map` branch, run:

    git co 04_map


Live demo
---------

You can try out the demo here:

* [http://geo-tweets.heroku.com/][d]


[tutorial]: http://vimeo.com/15672696

[00]: https://github.com/senchalearn/GeoTweets/tree/00_skeleton
[01]: https://github.com/senchalearn/GeoTweets/tree/01_gui
[02]: https://github.com/senchalearn/GeoTweets/tree/02_static
[03]: https://github.com/senchalearn/GeoTweets/tree/03_dynamic
[04]: https://github.com/senchalearn/GeoTweets/tree/04_map

[d]: http://geo-tweets.heroku.com/
