# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -

sudo apt-get install -y nodejs

# Or Using RHEL, CentOS, CloudLinux or Fedora:

curl -sL https://rpm.nodesource.com/setup_10.x | bash -

sudo yum install gcc-c++ make

# Next

npm install gitbook-cli -g

gitbook -V

gitbook init

gitbook install ./

gitbook serve

gitbook build

