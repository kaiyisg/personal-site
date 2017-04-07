---
layout: post
title:  "Heartbeat Monitor"
date:   2016-11-06 16:41:12 +0800
images:
  - url: "/images/heartbeat.png"
    alt: heartbeatmonitor
    title: heartbeatmonitor
category: 'Hardware'
description: "Analog-based remote heartbeat monitoring device"
skills: 
  - title: "Analog Circuit"
  - title: "Breadboarding"
  - title: "IR Transceiving"
---

Robust heart beat monitor

Building on top of basic analog components like LM358 Op Amps, I used photoplethysmography capturing tools to capture PPG signals, building a robust heart beat monitor. To be able to enable remote monitoring of a patient's heartbeat, I also built a remote transmission and receiving tool using IR transmitters and receviers. The receiver unit was also able to detect tachycardia (abnormally fast heart rate) using digital logic.
