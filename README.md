# docker-hello-world
This is just a place where i put the stuff that i did during the basic docker tutorial.
Easier to recall :)
## Install docker
```bash
# Uninstall older docker versions
sudo apt-get remove docker docker-engine docker.io

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
sudo apt-get update
sudo apt-get install docker-ce

sudo groupadd docker
sudo usermod -aG docker $USER

sudo systemctl enable docker

reboot
```

## Links
- [Tutorial Part 2: Containers](https://docs.docker.com/get-started/part2/)
- [Tutorial Part 3: Services](https://docs.docker.com/get-started/part3/)
- [Tutorial Part 4: Swarms](https://docs.docker.com/get-started/part4/)
- [Tutorial Part 5: Stacks](https://docs.docker.com/get-started/part5/)
