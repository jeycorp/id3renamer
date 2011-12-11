# id3renamer
by jamesob

dedicated to andy kirby. I owe that guy an email.

## don't pay money for a platform-specific gui

Tool for renaming all the MP3s in or below a directory based on ID3 tags.
Particularly useful after you've ripped your music off an iPod.

## dependencies

  - [id3Reader](http://nedbatchelder.com/code/modules/id3reader.html), included
    for posterity

## usage

    $ ./id3renamer.py -h
    usage: id3renamer.py [-h] [-d] [-v] path

    Walk a directory recursively and rename each MP3 found according to its ID3
    tags.

    positional arguments:
      path           Which directory to walk for MP3s.

    optional arguments:
      -h, --help     show this help message and exit
      -d, --dry-run  Do a dry run verbosely.
      -v, --verbose  Emit debugging information.



