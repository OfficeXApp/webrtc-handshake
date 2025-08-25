# WebRTC Signaling Server

## Development

```sh
npm i y-webrtc
PORT=4444 node ./bin/server.js
```

## Production

```sh
npm install -g pm2
PORT=4444 pm2 start ./bin/server.js --name y-webrtc-signaling
pm2 save
pm2 startup

# view logs
pm2 logs y-webrtc-signaling
```
# webrtc-handshake
