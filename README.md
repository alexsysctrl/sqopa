# sqopa — placeholder page

The static build of the page, ready for GitHub Pages: `index.html` and `logo-white.png`, no build step, no
dependencies, no CDN. Numbers are filled in by `../site/record.py`, which counts them from the log and
fails the build when a claim on the page stops being true — so **publish a build, never the source**, and
re-publish when the site is pushed (`../operations/site-push.sh` keeps this directory current).

Later this becomes something else and gets its own domain. Until then it is what it says it is: a
placeholder, so the name has a place and the place has a page.

To put it on Pages: create an empty public repo, push this directory to it as the default branch, and turn
Pages on for the root branch. A minute in the browser plus one `git push`.
