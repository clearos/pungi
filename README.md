# pungi

Forked version of pungi with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/pungi.git
* cd pungi
* git checkout epel7
* git remote add upstream git://pkgs.fedoraproject.org/pungi.git
* git pull upstream epel7
* git checkout clear7
* git merge --no-commit epel7
* git commit
