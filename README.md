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

### Live Streaming Servers

- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)**  
  **The leading open-source live streaming server**, MIT licensed with **29,000+ GitHub stars** . **Supports RTMP, WebRTC, HLS, HTTP-FLV, SRT, MPEG-DASH, and more** . **RTMP latency of 0.8–3s** ; **min-latency mode achieves ~0.1s for video-only streams** . **Scalable to millions of viewers** . **The de facto open-source Wowza alternative** . **Best for production live streaming** .

- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  
  **Ultra-low latency streaming engine with WebRTC (~0.5s)**, open-source with **4,700+ GitHub stars** . **Supports WebRTC, SRT, RTMP, HLS, CMAF, RTSP, and H.265/HEVC** . **SDKs for iOS, Android, React Native, Flutter, Unity, and JavaScript** . **Adaptive bitrate and cloud auto-scaling** . **Best for ultra-low latency interactive streaming** .

- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  
  **Sub-second latency live streaming server**, AGPL-3.0 licensed with **3,200+ GitHub stars** . **Supports WebRTC, LL-HLS, and SRT** for large-scale high-definition streaming . **Embedded live transcoder with ABR** . **DVR (Live Rewind)** and **DRM (Widevine, Fairplay)** . **Best for ultra-low latency with protocol flexibility** .

- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  
  **Ready-to-use zero-dependency live media server and media proxy**, MIT licensed with **20,000+ GitHub stars** . **Supports Media-over-QUIC, SRT, WebRTC, RTSP, RTMP, LL-HLS, MPEG-TS, and RTP** . **Automatic protocol conversion** — streams are converted from one protocol to another . **Single executable, no dependencies** . **Best for edge and simple deployments** .

- **[Nginx-RTMP](https://github.com/arut/nginx-rtmp-module)**  
  **RTMP streaming module for Nginx**, BSD-2-Clause licensed with **14,000+ GitHub stars** . **Simple RTMP streaming with HLS/DASH output** . **Best for simple RTMP streaming** .

### WebRTC Platforms

- **[LiveKit](https://github.com/livekit/livekit)**  
  **End-to-end realtime stack for connecting humans and AI**, Apache-2.0 licensed with **21,000+ GitHub stars** . **Scalable, distributed WebRTC SFU** written in Go using Pion . **Modern client SDKs for JavaScript, Swift, Kotlin, Flutter, React Native, and Rust** . **Built for production with JWT authentication and robust networking (UDP/TCP/TURN)** . **Easy to deploy: single binary, Docker, or Kubernetes** . **Best for building scalable real-time video applications** .

- **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)**  
  **General-purpose WebRTC server**, GPL-3.0 licensed with **9,100+ GitHub stars** . **Plugin architecture for VideoRoom, SIP, streaming, and more** . **Supports WebSockets, MQTT, RabbitMQ, and Data Channels** . **The reference for flexible WebRTC deployments** . **Best for custom WebRTC applications** .

- **[Jitsi Videobridge](https://github.com/jitsi/jitsi-videobridge)**  
  **WebRTC-compatible video router/SFU**, Apache-2.0 licensed with **3,100+ GitHub stars** . **Lets you build highly scalable video conferencing infrastructure** . **Powers Jitsi Meet** . **Best for scalable video conferencing** .

- **[mediasoup](https://github.com/versatica/mediasoup)**  
  **High-performance SFU library for WebRTC**, ISC licensed with **7,300+ GitHub stars** . **C++ core with Node.js signaling** . **Best for building custom WebRTC applications** .

### Additional Strong Open-Source Options

- **Jitsi Meet** — Secure, simple, and scalable video conferences (30,000+ stars) .
- **Pion WebRTC** — Pure Go WebRTC implementation (16,800+ stars) .
- **coturn** — High-performance TURN/STUN server for WebRTC (14,400+ stars) .
- **Owncast** — Self-hosted live streaming and chat (11,500+ stars) .
- **Node-Media-Server** — Node.js RTMP/HTTP-FLV media server (6,200+ stars) .
- **Restreamer** — Self-hosted live streaming UI and distribution server (5,200+ stars) .
- **OpenVidu** — WebRTC platform for building custom video apps (2,100+ stars) .
- **OBS Studio** — Open-source streaming software (77,000+ stars) .
- **Shaka Packager** — DASH/HLS packaging with DRM (2,600+ stars) .
- **FFmpeg** — The foundational multimedia framework (64,000+ stars) .
- **GStreamer** — Pipeline-based multimedia framework (3,300+ stars) .

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
