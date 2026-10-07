# Awesome-Low-Latency-Live-Video-Streaming

## Top Low-Latency Live Video Streaming Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Sub-Second Latency, Interactive Streaming & Self-Hosted Media Servers*  

**Last updated: October 2026**



This repository tracks notable **commercial low-latency streaming platforms** and **open-source projects** that deliver live video with sub-second to low-second latency — enabling interactive experiences, real-time communication, and scalable broadcasts without the typical HLS delay.



**Examples** include Amazon Interactive Video Service, Cloudflare Stream, Agora.io, Livepeer, Mux Video, Wowza Video, Phenix Real Time Solutions, Red5 Pro, Millicast (Dolby.io), and Dyte (the category leaders).



**Open-source emphasis**: Low-latency live streaming is one of the strongest open-source domains. **SRS** leads with 29,000+ GitHub stars supporting RTMP, WebRTC, SRT, and HLS . **Ant Media Server** delivers ultra-low latency WebRTC at ~0.5s with 4,700+ stars . **OvenMediaEngine** provides sub-second latency with LL-HLS and WebRTC at 3,200+ stars . **MediaMTX** offers a zero-dependency media router supporting SRT, WebRTC, and LL-HLS . **LiveKit** powers real-time video with 20,000+ stars . **Janus** provides a general-purpose WebRTC gateway with 9,100+ stars . **Jitsi Videobridge** enables scalable conferencing . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon Interactive Video Service (IVS)](https://aws.amazon.com/ivs/)**  

  **AWS's managed live streaming service** — built on the same technology as Twitch . **Sub-second latency with IVS Real-Time** and low-latency HLS with IVS Low-Latency . **Best for AWS-native interactive streaming** .



- **[Cloudflare Stream](https://www.cloudflare.com/products/stream/)**  

  **Cloudflare's video platform** — upload, store, and deliver video with global CDN . **Live streaming with low-latency HLS** . **Best for simple video delivery** .



- **[Agora.io](https://www.agora.io/)**  

  **Real-time engagement platform** — voice, video, and interactive streaming with sub-second latency . **Best for interactive live streaming and social applications** .



- **[Livepeer](https://livepeer.org/)**  

  **Decentralized video streaming** — open-source protocol with managed cloud . **Best for decentralized video infrastructure** .



- **[Mux Video](https://mux.com/)**  

  **API-first video platform** — ingest, transcode, and deliver video with real-time analytics . **Best for developer-friendly video** .



- **[Wowza Video](https://www.wowza.com/)**  

  **Enterprise live streaming platform** — low-latency streaming with adaptive bitrate and WebRTC support . **Best for broadcast-grade streaming** .



- **[Phenix Real Time Solutions](https://phenixrts.com/)**  

  **Real-time video streaming platform** — sub-second latency for live events and interactive applications . **Best for ultra-low latency at scale** .



- **[Red5 Pro](https://www.red5.net/)**  

  **Real-time streaming platform** — sub-second latency with WebRTC and autoscaling . **Best for interactive streaming applications** .



- **[Millicast (Dolby.io)](https://dolby.io/)**  

  **Real-time streaming platform** — WebRTC-based with sub-second latency . **Best for interactive video and audio** .



- **[Dyte](https://dyte.io/)**  

  **Real-time video and voice SDKs** — embed live video with low latency . **Best for developer-friendly video integration** .



## Open-Source GitHub Projects



### Live Streaming Servers



- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)**  

  **The leading open-source live streaming server**, MIT licensed with **29,206+ GitHub stars** . **Supports RTMP, WebRTC, HLS, HTTP-FLV, SRT, MPEG-DASH, and more** . **RTMP latency of 0.8–3s** ; **min-latency mode achieves ~0.1s for video-only streams** . **Scalable to millions of viewers** . **The de facto open-source Wowza alternative** . **Best for production live streaming** .



- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  

  **Ultra-low latency streaming engine with WebRTC (~0.5s)**, open-source with **4,727+ GitHub stars** . **Supports WebRTC, SRT, RTMP, HLS, CMAF, RTSP, and H.265/HEVC** . **SDKs for iOS, Android, React Native, Flutter, Unity, and JavaScript** . **Adaptive bitrate and cloud auto-scaling** . **Best for ultra-low latency interactive streaming** .



- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  

  **Sub-second latency live streaming server**, AGPL-3.0 licensed with **3,272+ GitHub stars** . **Supports WebRTC, LL-HLS, and SRT** for large-scale high-definition streaming . **Embedded live transcoder with ABR** . **DVR (Live Rewind)** and **DRM (Widevine, Fairplay)** . **Best for ultra-low latency with protocol flexibility** .



- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  

  **Ready-to-use zero-dependency live media server and media proxy**, MIT licensed . **Supports Media-over-QUIC, SRT, WebRTC, RTSP, RTMP, LL-HLS, MPEG-TS, and RTP** . **Automatic protocol conversion** — streams are converted from one protocol to another . **Single executable, no dependencies** . **Best for edge and simple deployments** .



- **[Nginx-RTMP](https://github.com/arut/nginx-rtmp-module)**  

  **RTMP streaming module for Nginx**, BSD-2-Clause licensed . **Simple RTMP streaming with HLS/DASH output** . **Best for simple RTMP streaming** .



### WebRTC Platforms



- **[LiveKit](https://github.com/livekit/livekit)**  

  **End-to-end realtime stack for connecting humans and AI**, Apache-2.0 licensed with **20,705+ GitHub stars** . **Scalable, distributed WebRTC SFU** written in Go using Pion . **Modern client SDKs for JavaScript, Swift, Kotlin, Flutter, React Native, and Rust** . **Built for production with JWT authentication and robust networking (UDP/TCP/TURN)** . **Easy to deploy: single binary, Docker, or Kubernetes** . **Best for building scalable real-time video applications** .



- **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)**  

  **General-purpose WebRTC server**, GPL-3.0 licensed with **9,159+ GitHub stars** . **Plugin architecture for VideoRoom, SIP, streaming, and more** . **Supports WebSockets, MQTT, RabbitMQ, and Data Channels** . **The reference for flexible WebRTC deployments** . **Best for custom WebRTC applications** .



- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)**  

  **WebRTC-compatible video router/SFU**, Apache-2.0 licensed with **3,103+ GitHub stars** . **Lets you build highly scalable video conferencing infrastructure** . **Powers Jitsi Meet** . **Best for scalable video conferencing** .



- **[mediasoup](https://github.com/versatica/mediasoup)**  

  **High-performance SFU library for WebRTC**, ISC licensed . **C++ core with Node.js signaling** . **Best for building custom WebRTC applications** .



### Additional Strong Open-Source Options



- **Jitsi Meet** — Secure, simple, and scalable video conferences (29,868+ stars) .

- **Pion WebRTC** — Pure Go WebRTC implementation .

- **OpenVidu** — WebRTC platform for building custom video apps .

- **OBS Studio** — Open-source streaming software (60,000+ stars) .

- **Restreamer** — Self-hosted live streaming .

- **Owncast** — Self-hosted live streaming and chat .

- **Shaka Packager** — DASH/HLS packaging with DRM .

- **FFmpeg** — The foundational multimedia framework .

- **GStreamer** — Pipeline-based multimedia framework .



**Frameworks for building custom low-latency streaming solutions**: Combine **SRS** for production live streaming with RTMP, WebRTC, and SRT . Use **Ant Media Server** for ultra-low latency WebRTC at ~0.5s with SDKs for every platform . Deploy **OvenMediaEngine** for sub-second latency with LL-HLS and WebRTC . Choose **MediaMTX** for zero-dependency edge deployments with automatic protocol conversion . Integrate **LiveKit** for scalable real-time video applications with modern SDKs . Use **Janus** for flexible WebRTC with plugin architecture . Note that true managed low-latency streaming with global infrastructure, automatic scaling, and vendor-supported SLAs (Amazon IVS, Agora, Phenix) remains primarily commercial territory; open-source stacks provide strong media servers, WebRTC platforms, and protocol flexibility that require integration for complete low-latency streaming deployments.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Low-latency streaming platforms handle bandwidth-intensive workloads and may process sensitive content. Self-hosted solutions require proper security hardening, bandwidth planning, and compliance with content regulations.

- **Latency vs. scalability trade-offs** — WebRTC delivers sub-second latency but scales to hundreds; LL-HLS scales to millions with 2–8 second latency . Standard HLS has 15–30 second latency . Choose based on your interactivity requirements.

- **Protocol selection matters** — WebRTC for interactive (<500ms), LL-HLS for large-scale low-latency broadcasts (2–8s), SRT for contribution feeds (0.5–2s), RTMP for ingest (2–5s) .

- **License considerations**: SRS uses MIT, Ant Media Server is open-source with Community/Enterprise editions , OvenMediaEngine uses AGPL-3.0, MediaMTX uses MIT , and LiveKit uses Apache-2.0 . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong media servers, WebRTC platforms, and protocol flexibility, but **global infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for streaming engineers, media developers, and organizations seeking low-latency streaming sovereignty.**  

Let's make low-latency live video streaming more open, transparent, and accessible.
