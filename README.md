# Heroku buildpack: Clojure / Boot / Org-Babel

This is a Heroku buildpack for use with Clojure projects that use Boot
and are written in a literate programming style with Org-Babel.

Based on https://github.com/pandeiro/heroku-buildpack-boot

## Work in progress

This is not working yet. I did experiment with multiple buildpacks via
https://github.com/ddollar/heroku-buildpack-multi and installing emacs via apt
through https://github.com/ddollar/heroku-buildpack-apt.
Emacs got installed, but binary is not found by other buildpacks then:
https://github.com/ddollar/heroku-buildpack-multi/issues/28

An alternative could be to use a prebuilt emacs binary like it's done in
https://github.com/technomancy/heroku-buildpack-emacs
