## Pipe Finder 1.0
Automated script to search in SMB protocol for availables pipe names

* Screenshots
- <img src="https://s2.postimg.cc/ceu9nan09/help.jpg" width="55%"></img>

- <img src="https://s2.postimg.cc/spudjjuc9/install.jpg" width="25%"></img><img src="https://s2.postimg.cc/w32m67b1l/ipscan.jpg" width="25%"></img><img src="https://s2.postimg.cc/k8uv85cnd/listscan.jpg" width="25%"></img>

# Requirements
- metasploit-framework
- wget
- locate
- pipe_audit_v2.rb module (https://github.com/peterpt/pipe_auditor_fb) - It will be installed on first run

# Install Requirements
- apt-get install metasploit-framework wget locate && updatedb
- (updatedb is only needed to cache the "locate" search database in order to get metasploit-framework directory)
# How to Run

- git clone https://github.com/peterpt/pipe_finder.git
- cd pipe_finder && ./pipef

# Notes :
This script can be copied to a system path , it will run independently .
