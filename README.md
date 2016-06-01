# xgetopt

A cross-platform implementation of legacy getopt related APIs:

* `xgetopt()`
* `xgetopt_long()`
* `xgetopt_long_only()`
* `xgetsubopt()`

The goal is to be a drop-in replacement of getopt APIs, so the using experience should be same as the legacy.

However, some tiny differences already exist between GNU and BSD's getopt implementations, xgetopt have to choose a side on each of those. Please refer to the comments inside xgetopt.h for the details.


