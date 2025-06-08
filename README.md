# 🎥 Frigate NVR – Optimized Configuration Snapshot

This repository includes a working configuration of Frigate NVR using:
- Dual EdgeTPUs (PCIe Coral)
- NVIDIA hardware decoding (CUDA/cuvid)
- go2rtc stream consolidation
- Audio support for Unifi/Sercomm cameras

## 📐 Goals
- Reduce CPU usage via GPU decoding
- Leverage EdgeTPU for faster object detection
- Maintain Birdseye functionality with high stream quality
- Optimize camera grouping and recording priorities

## ⚙️ Highlights
- Separate `detect` and `record` streams for each camera
- Audio enabled on supported feeds
- GPU load balancing via stream resolution and framerate
- Night/day motion tuning based on activity zones

## 🚫 Not Included
This is a **configuration showcase only**. It is not a development repo.

## 🧠 Why It Matters
This build was fine-tuned through real-world deployment and troubleshooting in a home security context involving multiple stream types and performance goals.
