# setup-guide

## Pre-setup
- Create a directory on your computer somewhere to keep everything related to GamaThon.
- Install Java 8.
- Install Intelli-J Community.
- Install Gradle (Easy to do with Chocolatey).
- Install NodeJS.
- Run `npm install http-server` in CMD.


## Setup client
This will run the client side on your computer. You will not need to connect to it directly. You will use the proxy for that.
- Open the GamaThon directory on your computer in CMD.
- Run `git clone https://github.com/GamaThon/tode-client.git` This will clone the client to your directory.
- Run `cd tode-client`
- Run `http-server -p 8002`


## Setup server
This will run the server. You need to run both at the same time.
- Open the GamaThon directory on your computer in CMD.
- Run `git clone https://github.com/GamaThon/tode-server.git`
- Open the folder in Intelli-J Community.
- In Intelli-J terminal run `gradle bootRun`

## Setup proxy (Windows)
- Open https://github.com/GamaThon/path-proxy/releases/tag/v1.0 in your browser.
- Download pproxy.exe to your `Gamathon` folder.
- Download the config
