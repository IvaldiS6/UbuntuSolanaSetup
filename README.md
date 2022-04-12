# UbuntuSolanaSetup
How I set up a Solana token generating VM on Google cloud free tier.  These are all of the commands I typed into the terminal.  

Comments start with "//"

Sample comment will look like the following:

//I needed to increase my swap size, I chose 5Gb
sudo mkdir /swapfile
sudo fallocate -l 5g /swapfile
//If that doesn't work try one of the following:
//sudo dd if=/dev/zero of=/swapfile bs=1024 count=5242876
//sudo dd if=/dev/zero of=/swapfile bs=1g count=5
