# README

This is a basic webserver meant to serve `site.test:80` as a dead end gateway - for letsencrypt http verification.

We enable some really basic configurations in `default.conf` and then we set the webroot which should have only one simple file. A `robots.txt` so that we can prevent crawlers from posting about this domain in search results.

There are two configuration files.

  1. `default.conf` - security defaults
  2. `site.test.conf` - points to web root where we have robots.txt
