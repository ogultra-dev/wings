
<h1 align="center">ogultra-daemon</h1>
## Overview
ogultra-daemon is the daemon for the ogultra-panel.

## Installation
1. Clone the repository:
`git clone https://github.com/ogultra-dev/wings`

2. go to panel directory:
`cd wings` 

3. Install dependencies:
`npm install`

6. add node ip:
```0.0.0.0```
 port:
```3002```

5. Configure ogultra:
- Get your Panel's access key from the ogultra-panel config.json file and set it as 'remoteKey'. Do the same for the other way, set your DracoDaemon access key and configure it on the Panel.

4. Start the Daemon:
`node . # or use pm2 to keep it online`
