# Setup Code

## Pre-setup
- Create a directory on your computer somewhere to keep everything related to GamaThon.
- Install Java 8.
- Install Intelli-J Community.
- Install Gradle (Easy to do with Chocolatey).
- Install NodeJS.
- Run `npm install -g http-server` in CMD.


## Setup client
This will run the client side on your computer. You will not need to connect to it directly. You will use the proxy for that.
- Open the `GamaThon` directory on your computer in CMD.
- Run `git clone https://github.com/GamaThon/tode-client.git` This will clone the client to your directory.
- Run `cd tode-client`
- Run `http-server -p 8002`


## Setup server
This will run the server. You need to run both at the same time.
- Open the `GamaThon` directory on your computer in CMD.
- Run `git clone https://github.com/GamaThon/tode-server.git`
- Open the folder in Intelli-J Community.
- In Intelli-J terminal run `gradle bootRun`

## Setup proxy (Windows)
- Open https://github.com/GamaThon/path-proxy/releases/tag/v1.0 in your browser.
- Download https://github.com/GamaThon/path-proxy/releases/download/v1.0/pproxy.exe to your `Gamathon` folder.
- Download the https://github.com/GamaThon/path-proxy/releases/download/v1.0/config.json to your `Gamathon` folder.
- In CMD run `pproxy`

## Setup proxy (*nix)
- `cd` to `Gamathon` folder.
- `go get github.com/GamaThon/path-proxy`
- Download https://github.com/GamaThon/path-proxy/releases/download/v1.0/config.json to GamaThon folder.
- `pproxy`

## Check the proxy
See if the proxy log says the following
```
INFO[0000] Mapping /websocket to http://localhost:8001
INFO[0000] Mapping / to http://localhost:8002
INFO[0000] Mapping /td to http://localhost:8002
```

## Open the app
- Open your browser
- Go to http://localhost:8000/


