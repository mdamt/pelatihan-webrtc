# ![webrtc](http://www.webrtc.org/_/rsrc/1318870658554/config/customLogo.gif?revision=8) Workshop

*"Imagine a world where your phone, TV and computer could all communicate on a common platform. Imagine it was easy to add video chat and peer-to-peer data sharing to your web application. That's the vision of WebRTC." — Sam Dutton*

**WebRTC** (Web Real-Time Communication) is an API drafted by the World Wide Web Consortium (W3C) that supports browser-to-browser applications for voice calling, video chat, and P2P file sharing without plugins.

## [Start the workshop!](WORKSHOP.md)

## Overview

### Topics

In this workshop, we will cover:

- What is WebRTC?
- What types of apps and features does WebRTC enable you to build?
- How to create WebRTC video/voice chat apps
  - How to create peer-to-peer connections in the browser
  - How to use `getUserMedia` to capture the user's webcam and microphone
  - How the "signaling process" allows us to connect two peers, and why it's necessary
  - How to write server-side (node.js) code to facilitate the signaling process
- How to create WebRTC data channel apps
  - How to send binary and text data
  - How to create reliable (tcp-like) and unreliable (udp-like) data channels
- How to handle browser differences

## Get excited

### Products using WebRTC

Check out some of the real-world products that make use of WebRTC:

- Simple video chat - [Talky](http://talky.io/) / [AppRTC](https://apprtc.appspot.com/)
- Simple file sharing - [ShareFest](http://sharefest.me)
- Peer-to-peer CDN - [PeerCDN](http://peercdn.com) / [Peer5](http://peer5.com) / [Swarmify](http://swarmify.com/) / [StreamRoot](http://www.streamroot.io/)
- Browse websites together with friends - [TogetherJS](https://togetherjs.com/)
- [Chromecast](http://www.webrtcworld.com/topics/from-the-experts/articles/347900-chromecast-webrtc.htm) - browser tab casting
- [Amazon Mayday](http://webrtchacks.com/mayday-trace/) - live kindle support
- [Snapchat](http://www.webrtcworld.com/topics/webrtc-world/articles/378013-wheelings-dealings-snapchat-acquires-webrtc-company-addlive.htm) - push-to-start video chat in a native app

### Experimental WebRTC Products

Mad scientists are pushing WebRTC to its limits. Check out these crazy projects:

- [Peer-Server](http://www.peer-server.com/) - a server backend in the browser
- [WebTorrent](http://webtorrent.io) - a streaming bittorrent client in the browser
- [WebRTC Plugin for old browsers](https://temasys.atlassian.net/wiki/display/TWPP/WebRTC+Plugins) - so you can make WebRTC work on IE9/10/11 and Safari

### WebRTC Vendors

- [AT&T](https://js.att.io/)
- [GoInstant](https://developers.goinstant.com/v1/widgets/audio_and_video/index.html)
- [Tokbox](http://tokbox.com/opentok/intro/)


## Sound awesome!?

Great! Here's how to get ready.

### Pre-Workshop Preparation

In order to prepare for this workshop, you should read the following articles before arriving at LXJS! If you have a question, please [open an issue](https://github.com/LXJS/training-webrtc/issues) and we will be glad to answer. You might be helping other participants!

### Todo List

- [ ] Check out [talky.io](https://talky.io/) and [sharefest.me](https://www.sharefest.me/)
- [ ] Check out the [first WebRTC call ever made](https://www.youtube.com/watch?v=MsAWR_rJ5n8). Historical!
- [ ] Read [Getting Started with WebRTC](http://www.html5rocks.com/en/tutorials/webrtc/basics/)
- [ ] Watch [Google I/O 2014 WebRTC presentation](https://www.youtube.com/watch?v=p2HzZkd2A40)
- [ ] Complete activities in "WebRTC Voodoo" workshopper -- coming soon...

### Additional Resources

These are not required, but if you want to hack on WebRTC code before you get to LXJS, you should check out the following links (with sample code!)

- [Cross-browser video/audio (adapter.js)](https://code.google.com/p/webrtc/source/browse/trunk/samples/js/base/adapter.js?r=3905)
- [Cross-browser data channel (webrtc-peer)](https://github.com/quartzjer/webrtc-peer/)

