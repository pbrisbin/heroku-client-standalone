PKGBUILD for installing [heroku-client][] standalone on Arch.

[heroku-client]: https://github.com/heroku/heroku

## Maintenance

Included here is a script that, when run, will:

- Check the unversioned upstream URL to see what version it really is
- If newer, update the PKGBUILD accordingly
- Present `git diff` for review
- Commit and tag the change
- Build the taurball and upload it via mkaurball and [aur-submit][]
- Test by installing the new version with [aurget][]

This script is [WTFPL][].

[aur-submit]: https://aur.archlinux.org/packages/aur-submit-git/
[aurget]:     https://aur.archlinux.org/packages/aurget/
[wtfpl]:      http://en.wikipedia.org/wiki/WTFPL
