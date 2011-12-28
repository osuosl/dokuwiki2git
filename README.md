dokuwiki2git
============

dokuwiki2git converts dokuwiki data directory into a git repository containing
the wiki pages, with proper history. Thus, migration to git-backed wiki engines
(eg. gollum) becomes easier.

Usage
-----

    $ dokuwiki2git /path/to/dokuwiki/data

This will create a git repository in `gitdir/`, containing the whole history of
the dokuwiki pages, one commit per change.

License
-------

dokuwiki2git is licensed under AGPLv3.

Contacting
----------

Bugs? Feature requests? Mail the author
