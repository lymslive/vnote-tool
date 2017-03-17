# vnote cmdline tools

The optional external cmdline tools for *vnote*
https://github.com/lymslive/vnote
migrates to here.

## Install

```
$ git clone https://github.com/lymslive/vnote-tool
$ cd right/path/to/vnote-tool
$ cd src
$ make
$ make install
```

Default install to `~/bin/vnote`

## Usage

To rebuild index for default notebook:

```
$ vnote -d ~/notebook -ctQ
```

To get a simple help:
```
$ vnote -?
```

To generate a test notebook:
```
$ cd right/path/to/vnote-tool
$ cd gen
$ ./genbox.pl ~/notebook-test
```

## Credit
https://github.com/tanakh/cmdline
A very light-weigth command line parser for C++.
