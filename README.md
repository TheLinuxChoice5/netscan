# netscan

Netscan is an shell script to perform Anonymous & Multi threaded port scan using netcat and proxychains 

![netscan](https://user-images.githubusercontent.com/34893261/39967102-57501cd8-568c-11e8-8d97-7c031947cc3f.png)

### Features
- Multi-thread
- Save/Resume sessions
- Anonymous scan through TOR
### Usage:
```
git clone https://github.com/TheLinuxChoice5/netscan
cd netscan
chmod +x netscan.sh
service tor start
./netscan.sh
```
Resume Session:
```
./netscan.sh --resume
```
### Install requirements (Tor, Proxychains, Netcat):

```
sudo apt-get install -y tor netcat
```
