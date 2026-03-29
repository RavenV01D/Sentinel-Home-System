# hackindia-spark-6-ncr-central-region-raven-pulse-labs
Hackathon team repository for Raven Pulse Labs - [hackindia-team:hackindia-spark-6-ncr-central-region:raven-pulse-labs]
# Hack India - Spark 6 Hackathon  
## Registered:  
### Team Name:   
Raven Pulse Labs  
**Name**:   
Arnav Arora  
### Profile:   
[https://hackindia.org/profile](https://hackindia.org/profile)  
### Under:   
Raven Pulse Labs  
### ID:   
HI005883  
## Details:  
### Data:   
18th April Saturday  
### Time:   
9:30 am  
### Place:   
NIT Delhi campus  
## Project:  
### Name:   
Raven Pulse Sentinel  
### Summary:   
No cloud, local security system and smart home  
### Description:   
RISC-V based raspberry pi edge computing security system, no cloud integration purely local, compatible with Raven Pulse NAS Server.  
### Problem Statement:  
Most modern smart home systems are built heavily on cloud infrastructure, exposing your data to 3rd parties where it can be leaked, sold and even weaponised for surveillance. I believe that personal data should remain personal and the current model of routing our private life’s through these companies is a fundamental security failure and in 2026 the cloud is no longer just a convenience but also a liability to your privacy. The future where your vulnerable is now and you can and should stop it. We should all take a stand and let go of subscription based survives where big tech controls everything in our lives and we own nothing. Raven Pulse Sentinel is my attempt to break away from these services and form a zero-trust model where you are once again in control of everything that enters and leaves your house.  
### Subparts:   
• Sentinel Hub: The central "Neural Node" (Raspberry Pi 5) that coordinates all devices, manages high-speed local traffic, and hosts the Private AI models.  
  
• Sentinel Pods: Low-power, ESP32-S3 voice-interface nodes. These feature Local Wake-Word Detection and secure audio I/O, acting as the "ears" of the system without cloud listening.  
  
• Sentinel Cam & Cam Swivel: Edge computing nodes (RPi Zero 2 W). The 'Swivel' variant features 3-Axis Precision Stepper Control for active tracking, with all video processing occurring locally on the device.  
  
• Sentinel Guard: A dedicated RISC-V (RP2350) security co-processor that acts as the Hardware Root of Trust, guarding encryption keys so they are never exposed to the main OS.  
  
• Sentinel-Net (PAN): A private, connectionless ESP-NOW mesh network. It allows Pods and Cams to communicate directly with the Hub, bypassing home Wi-Fi for sub-millisecond latency and zero-trust security.  
  
• Sentinel Console: A dedicated physical manager based on raspberry pi compute module 4 with a 5” display.  
• Sentinel Link: A high-performance Vue.js 3 PWA for cross-platform, remote control of the entire ecosystem.  
  
• Pulse NAS (Interlink): Support for Raven Pulse NAS Server, a 4 bay nas server build around a raspberry pi 5 for high speed network storage with no need for cloud connections.  
## To-Do List:  
- [ ] Complete The To-Do list
