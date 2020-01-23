---
title:  "Circuit design tutorials"
excerpt: "Good Circuit design references"

categories:
  - Circuit
tags:
  - Circuit
  - CMOS
last_modified_at: 2020-01-23

toc: true
---


# SSCS Lecture Slides
## Avoiding noise coupling in mixed signal design
+ [Designing CMOS Wireless System-on-a-chip](http://www.ewh.ieee.org/r6/scv/ssc/Sept2009.pdf): from page 18

[TODO] 제대로 읽고 내용 정리해서 남겨놓기 

## CDR 
+ [Clock and Data Recovery in HighSpeed Wireline Communications](http://www.ewh.ieee.org/r6/scv/ssc/May2109.pdf)
 + Design Strategy - system & architecture 
 + Circuit design example
  + Sampler (CML latch + Sense Amp. + Two-stage buffer)
  + Charge Pump / Loop filter
 + **Measurement Setup**
  + Overall setup
  + Jitter tolerance test: how to generate external sinusoidal jitter
  + Questions
   + **What is JTAG TAP & JTAP scan siganls?** Is JTAG insensitive to external noise?

## Analog

[TODO] 아래 링크 정리하자

[1 on-chip current reference](https://blog.naver.com/narabaljeon/220777097288)

## ADC/DAC

[chopper, bootrapped switch, amp, latch, etc...](http://www.ewh.ieee.org/r6/scv/ssc/Feb1209.pdf)

## LDO

[TODO] 아래 링크 정리하자

[1](https://blog.naver.com/narabaljeon/220818346841)
[2_good](https://blog.naver.com/narabaljeon/221095985247)
[3](https://site.ieee.org/scv-sscs/files/2010/02/LDO-IEEE_SSCS_Chapter.pdf)