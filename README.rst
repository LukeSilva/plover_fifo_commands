Plover Fifo Commands
====================
*Plugin which allows other applications to issue engine commands to plover*

**Setup**
This plugin allows other applications to issue engine commands to Plover, through the use of a named / FIFO pipe. It currently only works on Linux. The pipe can be found at: ``/tmp/PLOVER_CMD``. Commands can be issued like: ``echo "TOGGLE" >/tmp/PLOVER_CMD``
