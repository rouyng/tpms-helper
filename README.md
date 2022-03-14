# tpms helper
A bash shell script to partially automate Toyota tire pressure monitoring system testing via rtl_433.

I created this script as a companion to the TPMS sensor testing process described in [this article](https://www.r-c-y.net/posts/tpms/). This script is a wrapper for rtl_433 that provides guidance for this process, error handling and simple, human-readable output.

For more information on this script, [read this blog post](https://www.r-c-y.net/posts/tpmsbash/).

## Requirements
- [bash shell](https://www.gnu.org/software/bash/), version 4.0 or later
- [jq](https://stedolan.github.io/jq/)
- [bc](https://www.gnu.org/software/bc/)
- [rtl_433](https://github.com/merbanan/rtl_433)
- SDR hardware compatible with rtl_433

## Installing and running
```
git clone https://github.com/rouyng/tpms-helper.git
cd tpms-helper
chmod +x tpms-helper
./tpms-helper
```
