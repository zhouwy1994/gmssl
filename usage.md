## Prerequisite: build GmSSL core
1. check out github.com/guanzhi/GMSSL
1. Generate os-arch specific make file
  - run `SYSTEM=`uname -s` ./config --prefix=/usr/local/gmssl;`
1. build 
  - run `sudo make install_sw`
