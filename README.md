# SVN Grep

This script is adapted from [koto/svn-tools](https://github.com/koto/svn-tools/blob/8532b3303deef9ced43beaabc6ecb30c8f4a5881/svn-grep).

## Installation

1. Install [XMLStarlet](http://xmlstar.sourceforge.net/) (`brew install xmlstarlet` on Mac OS X with [Homebrew](http://brew.sh/)).
2. Install `svn-grep` on your PATH.

## Usage

```
svn-grep [-lvd] [-a <author>] [-m <message>] [svn_url]
	-l: show log messages
	-v: be verbose when showing log messages
	-d: show diff output
	-a: search by author
	-m: search by message
	-r: the svn revision argument
```
