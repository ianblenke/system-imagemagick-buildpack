# imagemagick buildpack

Installs imagemagick using a chroot-like snapshot of apt-get installed imagemagick and build dependencies.

This also caches the assets to speed things up further.

Best to use this as a multipack alongside heroku-buildpack-ruby

