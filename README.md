# autoconf-helper
config.guess and config.sub for aurora / VE

if your software ships a config.sub and config.guess not working for VE / Aurora,
please replace them with the ones here, and place uname in current directory.

Then you should be able to do

PATH=.:$PATH ./configure --host=ve-unknown-linux-gnu CC=/opt/nec/ve/bin/ncc CXX=/opt/nec/ve/bin/n++ 
