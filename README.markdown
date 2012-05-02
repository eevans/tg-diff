tg-diff
=======


Description
-----------
TopGit is a tool to make handling of interdependent topic branches easier. It is designed for the case when you need to maintain a queue of third-party patches on top of another (perhaps Git-controlled) project and want to easily organize and maintain them. 

tg-diff is a shell script that uses [Meld](http://meldmerge.org/) to open side-by-side diffs of TopGit patch output.

Requirements
------------
 * [meld](http://meldmerge.org/)
 * [patchutils](http://cyberelk.net/tim/software/patchutils/)
 * [TopGit](http://repo.or.cz/w/topgit.git)
