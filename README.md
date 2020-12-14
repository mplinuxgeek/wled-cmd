# wled-cmd
Simple command line interface for WLED devices

# requirements
There are only 2 tools called by this script:
curl
xmllint
- Fedora: dnf install libxml2
- Ubuntu: apt-get install libxml2-utils

# usage
```
./wled-cmd 192.168.1.147 on
./wled-cmd 192.168.1.147 color 255 0 0
./wled-cmd 192.168.1.147 color ff0000
./wled-cmd 192.168.1.147 brightness 128
./wled-cmd 192.168.1.147 cycle (this one cycles through a list of effects in the script)
./wled-cmd 192.168.1.147 fx 68
./wled-cmd 192.168.1.147 status
./wled-cmd 192.168.1.147 off
```
