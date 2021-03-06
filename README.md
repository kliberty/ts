This repository was forked from the most recent release on [http://vicerveza.homeunix.net/~viric/soft/ts/](http://vicerveza.homeunix.net/~viric/soft/ts/)

The primary repo location is [on bitbucket](https://bitbucket.org/kliberty/ts/src). <br>
There is a secondary mirror [on github](https://github.com/kliberty/ts)

Why this fork
-----------------
While `ts` already had `-k` to send a job `SIGTERM`, this fork adds `-z` and `-Z` to send `SIGSTOP` and `SIGCONT` respectively.

Adds a `-Q` option which behaves like the `TS_SOCKET` environment variable refered to in `TRICKS.md`. Using `-Q` will start multiple services allowing multiple queues to be used.

Users
------------------------
If you are in a system which understands POSIX and has the GNU toolkit, you
probably can run:
```
    make
    make install
```


If you want to install to another path than /usr/local, you can run:

```
    make install PREFIX=/usr
```


Developers
------------------------
Use 'bug' for the database.  http://freshmeat.net/projects/bug/ (this reports to the original author)

Use bitbucket or github to send an issue to me.
Run `. setenv` before adding bugs to the database.
