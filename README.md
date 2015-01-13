Axel's Sinfest RSS Generator
============================

This is a Perl written replacement for the
[broken/stale RSS feed](http://www.sinfest.net/rss.php) of the
daily webcomic [Sinfest](http://www.sinfest.net/).

Their RSS feed is stale since their site got a new design around the
8th of June 2014.

Usage
-----

By default it generates an RSS feed for the past 7 days and fetches
all titles from the website for that.

# Liferea

The script can be used as command-type source in
[Liferea](http://liferea.sf.net/). Actually it was written for exactly
that purpose.

Options
-------

* `-n`: Don't download anything from the Sinfest website, just generate
  a feed with dummy titles.
  
* `-d <number>`: Generate a feed for the past _<number>_ days.

License
-------

Copyright (C) 2015 Axel Beckert

Licensed under the _DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE_. See
the file LICENSE or http://www.wtfpl.net/txt/copying/ for the full
license text.
