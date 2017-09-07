
[install add-apt-repository for PPA]

sudo apt-get install apt-file

sudo apt-file update

sudo apt-get install software-properties-common

[set up proxy]

export http_proxy="http://proxygate1.nic.nec.co.jp:8080"

export https_proxy="http://proxygate1.nic.nec.co.jp:8080"

[install atom from PPA]

sudo -E add-apt-repository ppa:webupd8team/atom

sudo apt-get update

sudo apt-get install atom
