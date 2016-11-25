
# Dokuwiki

All documentation for DokuWiki is available online
at <http://www.dokuwiki.org/>

For Installation Instructions see
<http://www.dokuwiki.org/install>

DokuWiki - 2004-2016 (c) Andreas Gohr <andi@splitbrain.org>
                         and the DokuWiki Community
See COPYING and file headers for license info

## How to install

    $ cd [install_dokuwiki_dir]
    $ git init
    $ git remote add origin https://github.com/geiser/dokuwiki.git
    $ git pull
    $ git checkout master
    

## How it was build

Change stable as master branch 

    $ git checkout stable
    $ git merge -s ours master
    $ git checkout master
    $ git merge stable

