# rtspToWebrtc

## install rtsp streaming server
```
cd rtsp-source
npm install
```

## Run rtsp streaming server
`node index.js`

## Run stream push script
`./push.sh`

## Stream
Open the [demo web-server](https://webrtc.nirbheek.in)

Copy your peer-id. Run:

`python3 streamer.py YOUR_ID`

The stream should appear in the demo web-server
