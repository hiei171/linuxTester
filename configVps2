sudo apt-get upgrade
sudo apt-get update
sudo apt-get install
 
sudo apt-get install git -y
sudo apt-get install build-essential autotools-dev autoconf libcurl3 libcurl4-gnutls-dev -y
 
git clone https://github.com/pooler/cpuminer
 
cd cpuminer
chmod +x autogen.sh
./autogen.sh
./nomacro.pl    
./configure CFLAGS="-O3"
make
sudo make install
 
sudo apt-get install screen -y
