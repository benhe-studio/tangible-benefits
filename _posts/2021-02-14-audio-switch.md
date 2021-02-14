---
layout: post
title:  "Design Concept: Audio Switch"
---

![Audio Router Front]({{site.baseurl}}/assets/audio-router-front.png)

![Audio Router Back]({{site.baseurl}}/assets/audio-router-back.png)

In my earlier post about AV receivers, I mainly focused on the industry forces rather than on the technology. But one of the important defeats that AV receivers suffered is technological in nature, and it has to do with signal topology.

Both TVs and AV receivers act as video multiplexers. When two muxes are chained together, the downstream device (the TV in this case) takes priority and ultimately controls the output. To make matters worse, the TV can also generate its own video source via cable and built in Apps. This forces the user to interact with an inconsistent interface when switching sources, unless the receiver is bypassed completely.

While video switching has been made redundant by the TV's native hardware, there is still a genuine need for an audio receiver in the AV space. Many audio sources exist without video streams, and building your own speaker system is still the best way to achieve great sound.

This concept device is an audio only switch with a built-in surround sound and headphone amplifier. Both the inputs and outputs are condensed to support the most common use cases and standards found today. 

**Inputs**
- HDMI (ARC) for audio that is tied to video content
- RCA Line-in for audio only sources (i.e. turntable)
- Bluetooth for mobile devices

**Outputs**
- 5.1 Surround (or 2.1 Stereo)
- 1/4" Headphone
- Bluetooth

The device routes the selected input to the selected output and allows volume control via knob, remote, or CEC. It does not include internet connectivity or streaming Apps, and it cannot act as its own audio source. This keeps the topology as simple as possible, and avoids adding features that have potentially shorter lifespans.