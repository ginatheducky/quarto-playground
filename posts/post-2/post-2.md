---
title: "My Second Blog Post"
author: "Astro Learner"
description: "After learning some Astro, I couldn't stop! Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. After learning some Astro, I couldn't stop!"
image: italy.jpg
date: "6/22/2021"
categories:
  - news
  - code
  - 3Dprinting
  - test
  - galaxy
---
After a successful first week learning Astro, I decided to try some more. I wrote and imported a small component from memory!

Project Shortcode: RC  
Log: 001  
Date: 21/02/2026

This is the very first entry in my Maker Log. I want these logs to be a bit like lab journal notes - informal but structured, documenting what I tried, what worked, and what didn’t. I want them to be a real recollection of my journey of building a project. Today’s experiment is my first attempt at driving a brushless DC motor using a Raspberry Pi Pico and a cheap ESC. 

### Bill of Materials
- BLDC motor (from an old hover board)
- ESC ([ZS-X11H board with hall sensors](https://www.amazon.de/dp/B09DT8VQ72/ref=sspa_dk_detail_1?psc=1&pd_rd_i=B09DT8VQ72&pd_rd_w=LfQui&content-id=amzn1.sym.bf6dbf94-e926-4351-8952-c09f45cdef70&pf_rd_p=bf6dbf94-e926-4351-8952-c09f45cdef70&pf_rd_r=2SBBPVY53TC04RKV52BD&pd_rd_wg=xY6HT&pd_rd_r=597afc87-e0be-4a12-b49c-062a41a219b5&aref=FycRRDUKBN&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw))
- Arduino Uno
- Power Supply
- Jumper
- Pin header
- Wires
- Breadboard

### Salvaging the motor
It all started with someone else’s garbage. There’s a saying that one person’s trash is another person’s treasure, and in this case it was literally true. Someone left an old hoverboard in the garbage room of our apartment building (on a side note: you shouldn’t do that—there are recycling stations for old electronics).

Since I’ve always wanted to build a robot with brushless DC motors, I took it. The hoverboard has two motors—assuming they still worked. I didn’t have a charger, so I ordered a cheap one on Amazon, charged the board, and to my surprise it worked perfectly.

I disassembled the hoverboard and kept the two motors, the battery, and the metal motor mounts. I figured the mounts might be useful later for attaching the wheels to whatever chassis I end up building. The motor appears to be a 36V model; the label reads: WT36V20191214 JDBER1.

< add picture of the metal holders, the motors and the battery >

### Building a Test Setup