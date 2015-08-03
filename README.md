makemon - a replacement for nodemon
-----------------------------------

makemon is a basic replacement for nodemon that runs make before
executing a command (default: 'node $(find -name server.js)'.  It
monitors a directory (default: .) for changes and runs make and then
the command if make is successful.

Usage:

    makemon [directory to watch (recursively)] [command ...]

Example:

    makemon . node server.js

License:
--------

MIT

--
Burton Samograd
2015
