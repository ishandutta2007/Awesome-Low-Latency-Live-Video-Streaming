# Awesome-Low-Latency-Live-Video-Streaming

## Top Low-Latency Live Video Streaming Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Sub-Second Latency, Interactive Streaming & Self-Hosted Media Servers*  

**Last updated: October 2026**

This repository tracks notable **commercial low-latency streaming platforms** and **open-source projects** that deliver live video with sub-second to low-second latency — enabling interactive experiences, real-time communication, and scalable broadcasts without the typical HLS delay.

---

## Table of Contents

- [Market Overview](#market-overview)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Market Overview

**Estimated Sector Market Size & Industry Structure:**  
The global low-latency live video streaming market is estimated at **$1.8B – $2.5B in 2026**, projected to expand to **$6.5B+ by 2030** at a CAGR of ~21.5%. The sector is **moderately fragmented** (rather than winner-take-all) due to distinct architectural trade-offs: hyperscale clouds focus on cost-effective LL-HLS broadcast delivery, real-time API vendors specialize in sub-second WebRTC interactivity, and open-source media engines power self-hosted sovereignty.

---

## SaaS/Hosted Platforms

> *Platforms are sorted in descending order by estimated company size (annual revenue / valuation).*

| Platform / Product | Company Size (Revenue / Valuation) | Starting Tier Pricing | Free Tier / Trial Quota | Key Focus / Best For |
| :--- | :--- | :--- | :--- | :--- |
| **[Amazon Interactive Video Service (IVS)](https://aws.amazon.com/ivs/)** | ~$600B Revenue / ~$2.2T Market Cap *(AWS)* | $0.015/hr (ingest) + $0.075/hr (SD output) | 5 hrs live video input & 100 hrs output/mo free forever | AWS-native managed interactive streaming |
| **[Cloudflare Stream](https://www.cloudflare.com/products/stream/)** | ~$1.7B Revenue / ~$35B Market Cap *(Cloudflare)* | $5.00/mo (includes 1,000 min storage & 5,000 min view) | 10,000 minutes free trial credit (30-day trial) | Simple video delivery & low-latency HLS |
| **[Millicast (Dolby.io)](https://dolby.io/)** | ~$1.3B Revenue / ~$7.5B Market Cap *(Dolby Labs)* | $0.0055/GB transferred ($1.50/k participant mins) | $50 free credit on signup (valid forever) | Interactive WebRTC video & sub-second audio |
| **[Agora.io](https://www.agora.io/)** | ~$140M Revenue / ~$400M Market Cap *(Agora Inc.)* | $1.99 per 1,000 subscriber minutes (Audio/Video HD) | 10,000 free minutes per month (renews monthly forever) | Real-time engagement & social live streaming |
| **[Wowza Video](https://www.wowza.com/)** | ~$75M Revenue / ~$300M Valuation *(ClearLake Capital)* | $175.00/mo (includes 1,500 streaming hrs & 5 hr processing) | 30-day free trial (up to 1,000 peak connections / 10 hr processing) | Enterprise & broadcast-grade live streaming |
| **[Mux Video](https://mux.com/)** | ~$40M Revenue / ~$450M Valuation *(Series C)* | $0.04/min encoding + $0.0012/min delivery | $20 free trial credit (~500 encoding mins, valid indefinitely) | Developer-first video API & analytics |
| **[Livepeer](https://livepeer.org/)** | ~$300M FDV Market Cap / ~$5M Revenue *(Livepeer Studio)* | $0.005/min streaming ($0.003/min playback) | 1,000 streaming mins & 1,000 playback mins/mo free forever | Decentralized video streaming infrastructure |
| **[Phenix Real Time Solutions](https://phenixrts.com/)** | ~$15M Revenue / ~$90M Valuation *(Phenix RTS)* | $499.00/mo (Starter tier with 5,000 GB bandwidth) | 14-day free trial (up to 1,000 concurrent viewers & 50 GB bandwidth) | Ultra-low latency at broadcast scale |
| **[Red5 Pro](https://www.red5.net/)** | ~$8M Revenue / ~$30M Valuation *(Infrared5)* | $299.00/mo (Developer/Growth tier with autoscale clusters) | 30-day free trial (Developer license for 100 concurrent connections) | Interactive multi-party WebRTC streaming |
| **[Dyte](https://dyte.io/)** | ~$3M Revenue / ~$30M Valuation *(Y Combinator)* | $0.0015 per user-minute | 10,000 free user-minutes per month (renews monthly forever) | Developer-friendly live video & voice SDKs |

---

## Open-Source GitHub Projects

> *Repositories are sorted in descending order by GitHub star count. Star badges link directly to each repository's stargazers page.*

- **[OBS Studio](https://github.com/obsproject/obs-studio)** [![GitHub stars](https://img.shields.github.io/github/stars/obsproject/obs-studio?style=social)](https://github.com/obsproject/obs-studio/stargazers) — Free and open-source software for live video recording and live streaming.
- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)** [![GitHub stars](https://img.shields.github.io/github/stars/FFmpeg/FFmpeg?style=social)](https://github.com/FFmpeg/FFmpeg/stargazers) — Foundational cross-platform multimedia framework to record, convert, transcode, and stream audio/video.
- **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)** [![GitHub stars](https://img.shields.github.io/github/stars/jitsi/jitsi-meet?style=social)](https://github.com/jitsi/jitsi-meet/stargazers) — Secure, simple, and scalable WebRTC video conferencing standalone and embeddable application.
- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)** [![GitHub stars](https://img.shields.github.io/github/stars/ossrs/srs?style=social)](https://github.com/ossrs/srs/stargazers) — High-performance, production-ready real-time media server supporting RTMP, WebRTC, HLS, HTTP-FLV, SRT, and MPEG-DASH.
- **[LiveKit](https://github.com/livekit/livekit)** [![GitHub stars](https://img.shields.github.io/github/stars/livekit/livekit?style=social)](https://github.com/livekit/livekit/stargazers) — Scalable, distributed WebRTC SFU stack written in Go for real-time video, audio, and AI applications.
- **[MediaMTX](https://github.com/bluenviron/mediamtx)** [![GitHub stars](https://img.shields.github.io/github/stars/bluenviron/mediamtx?style=social)](https://github.com/bluenviron/mediamtx/stargazers) — Ready-to-use zero-dependency live media server and proxy supporting Media-over-QUIC, SRT, WebRTC, RTSP, RTMP, and LL-HLS.
- **[Pion WebRTC](https://github.com/pion/webrtc)** [![GitHub stars](https://img.shields.github.io/github/stars/pion/webrtc?style=social)](https://github.com/pion/webrtc/stargazers) — Pure Go implementation of the WebRTC API for building low-latency custom media pipelines.
- **[coturn](https://github.com/coturn/coturn)** [![GitHub stars](https://img.shields.github.io/github/stars/coturn/coturn?style=social)](https://github.com/coturn/coturn/stargazers) — High-performance TURN/STUN server project essential for WebRTC NAT traversal and media relaying.
- **[Nginx-RTMP Module](https://github.com/arut/nginx-rtmp-module)** [![GitHub stars](https://img.shields.github.io/github/stars/arut/nginx-rtmp-module?style=social)](https://github.com/arut/nginx-rtmp-module/stargazers) — NGINX extension for RTMP live streaming, video publishing, and HLS/DASH output generation.
- **[Owncast](https://github.com/owncast/owncast)** [![GitHub stars](https://img.shields.github.io/github/stars/owncast/owncast?style=social)](https://github.com/owncast/owncast/stargazers) — Self-hosted single-user live video streaming server with built-in interactive web chat.
- **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)** [![GitHub stars](https://img.shields.github.io/github/stars/meetecho/janus-gateway?style=social)](https://github.com/meetecho/janus-gateway/stargazers) — General-purpose C-based WebRTC gateway supporting plugin architectures for VideoRoom, streaming, and SIP.
- **[mediasoup](https://github.com/versatica/mediasoup)** [![GitHub stars](https://img.shields.github.io/github/stars/versatica/mediasoup?style=social)](https://github.com/versatica/mediasoup/stargazers) — Cutting-edge WebRTC SFU library designed with a C++ core and Node.js/Rust signaling bindings.
- **[Node-Media-Server](https://github.com/illuspas/Node-Media-Server)** [![GitHub stars](https://img.shields.github.io/github/stars/illuspas/Node-Media-Server?style=social)](https://github.com/illuspas/Node-Media-Server/stargazers) — Node.js implementation of RTMP, HTTP-FLV, and WebSocket-FLV live media server.
- **[Restreamer](https://github.com/datarhei/restreamer)** [![GitHub stars](https://img.shields.github.io/github/stars/datarhei/restreamer?style=social)](https://github.com/datarhei/restreamer/stargazers) — Complete streaming server solution for self-hosting with a visual UI to ingest and multi-publish streams.
- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)** [![GitHub stars](https://img.shields.github.io/github/stars/ant-media/Ant-Media-Server?style=social)](https://github.com/ant-media/Ant-Media-Server/stargazers) — Ultra-low latency streaming engine delivering ~0.5s WebRTC streams with auto-scaling and cross-platform SDKs.
- **[GStreamer](https://github.com/GStreamer/gstreamer)** [![GitHub stars](https://img.shields.github.io/github/stars/GStreamer/gstreamer?style=social)](https://github.com/GStreamer/gstreamer/stargazers) — Pipeline-based multimedia framework for constructing complex audio and video processing graphs.
- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)** [![GitHub stars](https://img.shields.github.io/github/stars/AirenSoft/OvenMediaEngine?style=social)](https://github.com/AirenSoft/OvenMediaEngine/stargazers) — Sub-second latency live streaming server supporting WebRTC and LL-HLS with embedded ABR transcoding.
- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)** [![GitHub stars](https://img.shields.github.io/github/stars/jitsi/jitsi-videobridge?style=social)](https://github.com/jitsi/jitsi-videobridge/stargazers) — WebRTC-compatible Selective Forwarding Unit (SFU) router designed for high-concurrency video conferencing.
- **[Kurento Media Server](https://github.com/Kurento/kurento-media-server)** [![GitHub stars](https://img.shields.github.io/github/stars/Kurento/kurento-media-server?style=social)](https://github.com/Kurento/kurento-media-server/stargazers) — WebRTC media server offering media pipelines, computer vision capabilities, and real-time video filters.
- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)** [![GitHub stars](https://img.shields.github.io/github/stars/shaka-project/shaka-packager?style=social)](https://github.com/shaka-project/shaka-packager/stargazers) — Media packaging framework for VOD and Live DASH/HLS applications supporting Common Encryption (CENC) and DRM.
- **[OpenVidu](https://github.com/OpenVidu/openvidu)** [![GitHub stars](https://img.shields.github.io/github/stars/OpenVidu/openvidu?style=social)](https://github.com/OpenVidu/openvidu/stargazers) — Self-hosted real-time video and audio application platform built on top of LiveKit and mediasoup.
- **[Membrane Framework](https://github.com/membraneframework/membrane_core)** [![GitHub stars](https://img.shields.github.io/github/stars/membraneframework/membrane_core?style=social)](https://github.com/membraneframework/membrane_core/stargazers) — Modular multimedia processing framework written in Elixir for building scalable audio/video pipelines.

---

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
