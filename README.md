## StackExchange xml dump converter

Creates sqlite3 db and inserts all data from specified site archive into it.

Works with May 2, 2014 data dump.

### Usage

* decompress archive with choosen site dump into directory with this script.
* On nix systems all file names must be lowercased
* run `makedb.py`

It still is python2+ code.

It was tested only with stackoverflow-part of data dump.

## Acknowledgement

It is light improvement of [this code](http://meta.stackexchange.com/questions/28103/python-script-to-import-create-sqlite3-database-from-so-data-dump)
(all tables inserted and stuff...)


