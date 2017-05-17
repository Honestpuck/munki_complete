## bash completion for the Munki command line tools

These are a number of scripts designed to add programmable completion to `bash` for all
the command line tools used by Munki.

They complete the long options for each tool, the completion cuts in after `-`. For
manifestutil it completes on the commands and then the right long options for each
command.

**Note** `munkiimport` supports all the options for`makepkginfo` which means a long
list of possible completions. I've made adding the `makepkginfo` options a different
assignment from the standard ones so you can easily remove them if you wish.

If you have installed bash completion using `brew` then drop the files
into `/usr/local/etc/bash_completion.d/` (or link them) and open a new Terminal window.

Feedback, bug reports and comments would be greatly appreciated.