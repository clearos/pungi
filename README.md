# pungi

Forked version of pungi with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/pungi.git
* cd pungi
* git checkout f13
* git remote add upstream git://pkgs.fedoraproject.org/pungi.git
* git pull upstream epel6
* git checkout clear6
* git merge --no-commit epel6
* git commit
