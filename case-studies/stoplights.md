# 🟢 Office Stoplight Project

### *Solving a real problem, one blinking light at a time.*

---

## Overview

What started as a simple “Wouldn’t it be easier if…” moment turned into an 18-month exploration of hardware, networking, 3D printing, and human-centered design. I wasn’t trying to build a full-stack solution, I just didn’t want to get interrupted while teaching. But the project had other plans.

I've shared the code, specifications, and that first enclosure pattern [here](https://github.com/robert-bills/maker-projects/tree/master/stoplight-status-indicator).  

---

## The Problem

A few months after joining Rapid7 as a Senior Instructor, we moved to a quiet neighborhood in Colorado Springs. I finally had my own office—a separate outbuilding next to my wife’s costume shop. It was a dream setup, until we started organizing her gear and I found myself facing a recurring challenge:  
**“Oops, didn’t know you were busy.”**

Signs and magnets helped, but they weren’t enough during live sessions. That’s when I uttered the seven words that send makers spiraling into greatness (or madness):  
**“There has to be an easier way.”**

---

## Building the System

### 🧪 Early Prototype
The first version was rough: a Raspberry Pi Zero W taped to the wall, reclaimed CAT6 cable running to a breadboard, and Python commands sent over VNC. It worked—but only just.

### 📡 Wireless Iteration
I learned how to flash MicroPython onto an ESP8266 microcontroller and set up a Raspberry Pi 3 as a base station. I built a lightweight UDP broadcast system to send `Red`, `Yellow`, or `Green` signals through the network. A simple heartbeat protocol helped keep devices in sync even if they were unplugged and reconnected.

### 🖥️ Interface Upgrade
Eventually, I replaced the CLI selector with a Python GUI—just a few buttons, but enough to change my status with a click from anywhere on my property. I placed receiver boxes in the kitchen and outside my office door so others could see my status at a glance.

---

## Making It Presentable

At my family’s (reasonable) request, I began exploring enclosure options. My first “case” was cardboard taped together—not exactly a looker. But with a new 3D printer in the house (courtesy of my son’s cosplay plans), I dove into CAD and learned to design something better.

My first successful two-piece print was a flimsy, awkward little enclosure—but it worked. It held the lights. It housed the board. It *did its job*. And I’ll never get rid of it.

---

## Lessons Learned

I didn’t plan on building a networked hardware control system, learning 3D modeling, writing a GUI, or exploring embedded microcontrollers—but the project asked for all of that and more.

If I’d known the scope from the beginning, I might have backed away. But honestly? I’m glad I didn’t.  
Changing the sign really was a pain.

And sitting on my shelf today is that little plastic box with flimsy sides.  
It’s not sleek. It’s not strong.  
But it reminds me of the most important lesson:  
**You don’t have to be perfect. You just have to get started.**
