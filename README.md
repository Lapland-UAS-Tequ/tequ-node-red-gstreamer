tequ-node-red-gstreamer
=====================

Launch and control GStreamer pipelines.

## Install

Run the following command in your Node-RED user directory - typically `~/.node-red`

        npm install Lapland-UAS-Tequ/tequ-node-red-gstreamer

## Information

Launch and control GStreamer pipelines using exec-node.

GStreamer pipeline settings are configured in node config.

Input command is sent in "msg.topic"

Available commands:
- start (starts GStreamer pipeline)
- restart (restart GStreamer pipeline))
- kill (Terminates running pipeline))

Outputs stderr, stdout and error from exec-node.

Supported video sources
- pylonsrc (https://github.com/basler/gst-plugin-pylon)
- v4l2src
