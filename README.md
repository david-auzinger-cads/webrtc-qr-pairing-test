# WebRTC QR pairing test

Test page: a phone and a laptop linked by a WebRTC data channel, with no signalling server and no STUN/TURN.
Pairing is done with QR codes only. Photos taken on the phone go directly to the laptop over the local network.

Open https://david-auzinger-cads.github.io/webrtc-qr-pairing-test/ on both devices and choose the role.
The phone reads the laptop's QR code with its camera; on the first pairing the laptop webcam then reads the phone's QR code.
