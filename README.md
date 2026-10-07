# Awesome-Media-Storage-Live-Video-Streaming

# Top Media Storage & Live Video Streaming Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Video Storage, Live Streaming & Self-Hosted Media Delivery*  
**Last updated: October 2026**

This repository tracks notable **commercial media storage and streaming platforms** and **open-source projects** that store, transcode, and deliver live and on-demand video — from CDN-integrated media stores to self-hosted streaming servers and origin platforms.

**Examples** include AWS Elemental MediaStore, Fastly Streaming Media, Akamai Adaptive Media Delivery, Cloudflare Stream, Mux Video, Wowza Streaming Engine, Brightcove Video Cloud, Vimeo Enterprise, Limelight Networks, and Bunny.net Stream (the category leaders).

**Open-source emphasis**: Media storage and live streaming is one of the strongest open-source domains. **SRS**, **MediaMTX**, **Ant Media Server**, and **OvenMediaEngine** deliver production-grade live streaming with RTMP, SRT, and WebRTC. **LiveKit** and **Jitsi** power real-time video. **Owncast** enables self-hosted broadcasting. **MinIO** and **Ceph** provide S3-compatible media storage. **FFmpeg** and **GStreamer** handle transcoding. **Shaka Packager** and **Bento4** manage packaging and DRM. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS Elemental MediaStore](https://aws.amazon.com/mediastore/)**  
  **AWS's media-optimized storage** — high-performance object storage for live and on-demand video . **Low-latency origin for MediaPackage and CloudFront** . **Best for AWS-native video workflows** .

- **[Cloudflare Stream](https://www.cloudflare.com/products/stream/)**  
  **Cloudflare's video platform** — upload, store, and deliver video with global CDN . **Best for simple video delivery** .

- **[Mux Video](https://mux.com/)**  
  **API-first video platform** — ingest, transcode, and deliver video with analytics . **Best for developer-friendly video** .

- **[Wowza Streaming Engine Cloud](https://www.wowza.com/)**  
  **Enterprise live streaming platform** — low-latency streaming with adaptive bitrate . **Best for broadcast-grade streaming** .

- **[Brightcove Video Cloud](https://www.brightcove.com/)**  
  **Enterprise video platform** — OTT, live streaming, and monetization . **Best for enterprise video** .

- **[Vimeo Enterprise](https://vimeo.com/enterprise)**  
  **Enterprise video platform** — hosting, live streaming, and collaboration . **Best for enterprise video** .

- **[Fastly Streaming Media](https://www.fastly.com/)**  
  **Edge cloud for media delivery** — high-performance CDN for video streaming . **Best for edge delivery** .

- **[Akamai Adaptive Media Delivery](https://www.akamai.com/)**  
  **Global CDN for media** — adaptive bitrate streaming at scale . **Best for large-scale delivery** .

- **[Limelight Networks](https://www.limelight.com/)**  
  **CDN and edge cloud for media** — video delivery and edge compute . **Best for media delivery** .

- **[Bunny.net Stream](https://bunny.net/)**  
  **Video streaming CDN** — simple, cost-effective video delivery . **Best for cost-effective streaming** .

## Open-Source GitHub Projects

### Live Streaming Servers

- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)**  
  **The leading open-source live streaming server**, MIT licensed with **25,000+ GitHub stars** . **Supports RTMP, HLS, SRT, WebRTC, and DASH** . **Scalable to millions of viewers** . **The de facto open-source Wowza alternative** . **Best for production live streaming** .

- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  
  **Zero-dependency real-time media server**, MIT licensed with **10,000+ GitHub stars** . **Supports SRT, WebRTC, RTSP, RTMP, HLS, and LL-HLS** . **Single binary with no dependencies** . **The simplest path to low-latency streaming** . **Best for edge and IoT streaming** .

- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  
  **Ultra-low latency streaming server**, Apache-2.0 licensed with **4,000+ GitHub stars** . **Sub-second latency with WebRTC** . **Adaptive bitrate, recording, and scaling** . **Best for ultra-low latency streaming** .

- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  
  **Sub-second latency streaming server**, AGPL-3.0 licensed with **3,000+ GitHub stars** . **LLHLS, WebRTC, and SRT support** . **Best for ultra-low latency** .

- **[Nginx-RTMP](https://github.com/arut/nginx-rtmp-module)**  
  **RTMP streaming module for Nginx**, BSD-2-Clause licensed . **Simple RTMP streaming with HLS/DASH output** . **Best for simple RTMP streaming** .

- **[Owncast](https://github.com/owncast/owncast)**  
  **Self-hosted live streaming and chat**, MIT licensed with **10,000+ GitHub stars** . **Own your live stream** . **Best for independent broadcasters** .

### Media Storage & Origin

- **[MinIO](https://github.com/minio/minio)**  
  **The de facto standard for S3-compatible object storage**, AGPL-3.0 licensed with **50,000+ GitHub stars** . **High-performance media storage** for video origin . **Best for S3-compatible media storage** .

- **[Ceph](https://github.com/ceph/ceph)**  
  **Unified distributed storage system**, LGPL-2.1 licensed . **Object, block, and file storage** — scales to petabytes . **Best for unified media storage** .

- **[SeaweedFS](https://github.com/seaweedfs/seaweedfs)**  
  **Fast distributed storage for billions of files**, Apache-2.0 licensed . **S3 API compatible** . **Best for large-scale media storage** .

- **[Garage](https://git.deuxfleurs.fr/Deuxfleurs/garage)**  
  **Lightweight, distributed S3-compatible object storage**, AGPL-3.0 licensed . **Designed for self-hosting** . **Best for small to medium media storage** .

### Transcoding & Packaging

- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)**  
  **The foundational multimedia framework**, LGPL/GPL licensed . **The engine behind most streaming platforms** . **Best for media processing and transcoding** .

- **[GStreamer](https://github.com/GStreamer/gstreamer)**  
  **Pipeline-based multimedia framework**, LGPL licensed . **Modular media processing** . **Best for custom media pipelines** .

- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)**  
  **Media packaging SDK**, Apache-2.0 licensed . **DASH, HLS, and CMAF packaging with DRM** . **Best for multi-format packaging** .

- **[Bento4](https://github.com/axiomatic-systems/Bento4)**  
  **MP4 and DASH tooling**, GPL-3.0 licensed . **DASH segmenting and encryption** . **Best for DASH packaging** .

- **[GPAC](https://github.com/gpac/gpac)**  
  **Multimedia framework with DASH/HLS support**, LGPL licensed . **Packaging, encryption, and streaming tools** . **Best for comprehensive media packaging** .

### WebRTC & Real-Time Video

- **[LiveKit](https://github.com/livekit/livekit)**  
  **Open-source WebRTC platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Scalable SFU architecture** . **SDKs for all platforms** . **Best for real-time video applications** .

- **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)**  
  **The leading open-source video conferencing platform**, Apache-2.0 licensed with **25,000+ GitHub stars** . **WebRTC-based with scalable SFU** . **Best for video conferencing** .

- **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)**  
  **General-purpose WebRTC server**, GPL-3.0 licensed . **Plugin architecture** . **Best for flexible WebRTC** .

- **[mediasoup](https://github.com/versatica/mediasoup)**  
  **High-performance SFU library**, ISC licensed . **C++ core with Node.js signaling** . **Best for custom WebRTC applications** .

### Additional Strong Open-Source Options

- **OBS Studio** — Open-source streaming software .
- **Restreamer** — Self-hosted live streaming .
- **Kurento** — WebRTC media server .
- **Pion WebRTC** — Pure Go WebRTC .
- **OpenVidu** — WebRTC platform .
- **Shaka Player** — Open-source video player .
- **hls.js** — JavaScript HLS client .
- **dash.js** — JavaScript DASH client .
- **Video.js** — Open-source player framework .

**Frameworks for building custom media storage and live streaming solutions**: Combine **SRS** or **MediaMTX** for production live streaming with RTMP, SRT, and WebRTC . Use **Ant Media Server** or **OvenMediaEngine** for ultra-low latency sub-second streaming . Deploy **MinIO** or **Ceph** for S3-compatible media storage . Integrate **FFmpeg** and **GStreamer** for transcoding . Choose **Shaka Packager** or **Bento4** for DASH/HLS packaging with DRM . Use **LiveKit** or **Jitsi** for real-time video . Note that true managed media storage and streaming with global CDN, automatic scaling, and vendor-supported SLAs (Cloudflare Stream, Mux, Wowza) remains primarily commercial territory; open-source stacks provide strong streaming servers, media storage, and transcoding foundations that require integration for complete media delivery.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Media storage and streaming platforms handle bandwidth-intensive workloads and may process copyrighted content. Self-hosted solutions require proper security hardening, bandwidth planning, and compliance with content regulations.
- **Latency vs. scalability trade-offs** — WebRTC delivers sub-second latency but scales to hundreds; HLS/DASH scales to millions but adds 6-30 seconds latency. Choose based on use case .
- **Bandwidth costs scale linearly** — each viewer consumes bandwidth. Self-hosted streaming requires CDN or adequate egress capacity .
- **DRM licensing is complex** — Widevine, FairPlay, and PlayReady require licensing agreements. Shaka Packager and Bento4 support DRM packaging but do not provide licenses .
- **License considerations**: SRS uses MIT, MediaMTX uses MIT, Ant Media uses Apache-2.0, OvenMediaEngine uses AGPL-3.0, and MinIO uses AGPL-3.0. Verify licensing against your use case before committing.
- The open-source ecosystem provides strong streaming servers, media storage, and transcoding foundations, but **global CDN, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for streaming engineers, media developers, and organizations seeking media storage and streaming sovereignty.**
Let's make media storage and live video streaming more open, transparent, and accessible.
