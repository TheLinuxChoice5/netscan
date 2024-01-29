# netscan

Netscan is an shell script to perform Anonymous & Multi threaded port scan using netcat and proxychains 

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
