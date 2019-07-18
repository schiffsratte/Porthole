# Porthole
some Porthole stuff

my own changes to porthole for newer portage versions.
It's to make porthole work again, but it's not a 
proper update to porthole

***works for me, may not work for anybody else***

I use it with Python 2.7.15, just replace  (or diff)
the files in /usr/lib64/python2.7/site-packages/porthole/
with the contents of this repo

This files have modifications: 
porthole/advancedemerge/advemerge.py
porthole/backends/portagelib.py
porthole/db/user_configs.py
porthole/views/changelog.py (only debugging, not important)
