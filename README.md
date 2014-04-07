aps-length
==========

(c) James Kermode <james.kermode@gmail.com> 2014

Usage: aps-length [options] tex-files

Count number of equivalent words in an APS manuscript formatted in
LaTeX, following guidelines described at http://journals.aps.org/authors/length-guide

Requires _detex_ (http://www.ctan.org/pkg/detex) and ImageMagick
_identify_ (http://www.imagemagick.org) to be available on your path.

Options:

    -h, --help            show this help message and exit
    -v key value, --var=key value
                          Define TeX variables e.g. to specify location of
                          figure files.
    -e env1,env2,..., --env=env1,env2,...
                          Comma-separated list of LaTeX environments to ignore.
    -j PRL, --journal=PRL
                          Journal abbreviation (e.g. PRL, PRB-RC)

