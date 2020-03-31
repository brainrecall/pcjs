---
layout: page
title: IBM PC (Model 5150) with VGA Display and Debugger
permalink: /machines/pcx86/ibm/5150/vga/debugger/
machines:
  - id: ibm-5150-vga
    type: pcx86
    config: /configs/pcx86/ibm/5150/machine-vga-debugger.json
    autoMount:
        A:
            name: Invaders Boot Sector
        B:
            name: None
---

{% include machine.html id="ibm-5150-vga" %}