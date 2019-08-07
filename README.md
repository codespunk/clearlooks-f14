## Overview

This is a fork of [Clearlooks-Phenix](https://github.com/jpfleury/clearlooks-phenix), a project originally started by [Jean-Philippe Fleury](https://github.com/jpfleury) as a GTK3 port of Clearlooks, the default theme of GNOME 2.

While originally meant to be a simple fork with some patches to push upstream, I later decided that my own goals were somewhat different and have since renamed the project Clearlooks-14. This project, while similar in scope and a shared love for Clearlooks, I want to creare a theme which more closely resembles the customized Clearlooks theme which was distributed with Fedora 14.

Clearlooks-Phenix has been a good holdover for me but changes in GTK3 have slowly broken many parts of it. And these problems are glaring and unpleasant. I've also missed the look of the Fedora 14 desktop environment, of which I feel is one of the finest representations of Linux on the desktop.

So, here it is. Clearlooks-14. I've only just started working on it but I've already fixed a lot of bugs which have cropped up between the last commit to Clearlooks-Phenix and the latest theme-breaking changes provided by the GNOME Project. Please feel free to try it out and report any issues you find.

Note that I am only testing this on Fedora and tracking the latest GTK3 release. So there will most likely be problems and inconsistencies for anyone using it with older versions of GNOME 3-- I simply haven't done any testing with any other version.

---

Note that it can be difficult to identify what exactly has changed from my commits without applying the theme and comparing it with an older release. To aid in pushing changes upstream, to highlight bug fixes, and to help backport these changes to older GTK3 style sheets, I am tracking these changes as I make them in the [issues](https://github.com/codespunk/clearlooks-f14/issues) section of this project. View the **closed** tickets to see pictures of each individual change that been made.
