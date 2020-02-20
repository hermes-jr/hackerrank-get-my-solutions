# HackerRank Submissions Downloader 

[![Build Status][build_status_svg]][build_status_link]

## Usage

```
java -jar hackerrank-downloader.jar [-d <PATH>] [-f] [-h] [-l <NUMBER>] [-o <NUMBER>] [-v]
 -d,--directory <PATH>   path to output directory. Default: current
                         working directory
 -f,--force-overwrite    Force overwrite if output directory exists. May
                         lead to data loss.
 -h,--help               display this help and exit
 -l,--limit <NUMBER>     number of solved challenges to download. Default
                         is 65535
 -o,--offset <NUMBER>    number of items to skip. Default is 0
 -v,--verbose            run in verbose mode

Application expects a file .hackerrank-downloader-key to exist in your
home directory. It must contain a single ASCII line, a value of
"_hrank_session" cookie variable
```

[build_status_link]: https://travis-ci.org/hermes-jr/hackerrank-get-my-solutions.svg?branch=master