# GPX Combiner

A simple Python script for combining a bunch of GPX files into one. I wrote it
because I wanted a tool to help me work out where in Leicester I had not yet
cycled and the otherwise brilliant [GPX Reader](http://gpxreader.fousa.be/)
does not support displaying multiple GPX files on the same map.

## Setup and Use

You'll need some version of Python 2.7 and [lxml](http://lxml.de/), which you
should be able to install with `pip install lxml`. If not, have a look at
[their instructions](http://lxml.de/installation.html#installation).

I invoke the script as follows:

```bash
~/code/gpx-combiner/combiner.py ~/cycles/ > all_cycles.gpx
```
