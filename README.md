# Description
This is a minimal working example of controlling a video through MQTT. It's very bare bones but can be used as a template for getting started with MQTT and javascript.

## Getting Started
This assumes you already have an MQTT broker that will be sending the MQTT messages. To connect this as a client change the hostname in 'index.html'. The port 1884 matches the default Websocket Port in home assistant. 

**You need to place a video named 'video.mp4' in this folder**. One is not included to prevent licensing issues.

You may need to enable "autoplay" in your browser for this site. Most browsers disable autoplay by default. 