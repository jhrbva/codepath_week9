# CodePath Week 9 - Honeypot

Honeypots deployed: Only mhn-honeypot-1

###Attacks
The first attack I viewd was my own.
The next one came after about 45min. After that I got about 200 attacks every 2sec or so, from the same IP in China (134.175.134.240).
I had two U.S attacks after that, before downloading the `json` file and exiting the project.

###Issues
I ran into an issue in Milestone 2, where the intructions say:
`$ cd /opt`
`$ sudo git clone https://github.com/RedolentSun/mhn.git`
`$ cd mhn`
`$ sudo ./install.sh`

When I ran the last line, it asked for my git credentials but it ended in error.

I asked a classmate who suggested I try `$ sudo git clone https://github.com/threatstream/mhn.git` instead.
Not sure what the issue was here, but this solution worked for me.

