# 🗄 FileServer

**This is a simple file server that allows you to upload files to the server.**
<br>
You can upload files to the server and then get download links to them.

- _If you using heroku, After heroku restarts all files will be deleted!_

## Deploy
**Deploy to Heroku**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/HEARTBEAT-77/FileServer)

-----
**Deploy to VPS**

_Steps:_
- Install go in your server.
- Clone repo. `git clone https://github.com/AnjanaMadu/FileServer && cd FileServer`
- Install libs. `go mod tidy`
- Build app. `go build`
- Grant premissions. `chmod +x FileServer`
- Run app. `./FileServer`


## Credits
- [**Me**](https://github.com/AnjanaMadu)
- [**Echo**](https://github.com/labstack/echo/) web framework
