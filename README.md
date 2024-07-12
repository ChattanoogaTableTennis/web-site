# web-site

This is the souce code for the chattanoogatabletennis.com site.
It uses [Lektor](https://www.getlektor.com/) to manage the building of the site.

The process of updating is a follows:

* clone this site
* run lektor serve and view locally to update
* check what has changed: `git status`
* commit the changes: `git commit -a`
* send changes to github: `git push`
* github actions will update the web site
