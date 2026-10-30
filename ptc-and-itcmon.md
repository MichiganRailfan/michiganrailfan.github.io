---
layout: default
title: PTC and ITCMon
---

# PTC and ITCMon

## Table of Contents

- [What is Positive Train Control?](#what-is-positive-train-control)
- [What is an SDR? Which should I buy?](#what-is-an-sdr-which-one-should-i-buy)
- [About ITCMon and it's ancestors](#about-itcmon-and-its-ancestors)

## What is Positive Train Control?

Positive Train Control (PTC) is a system used by basically all railroads in the United States to control speed, stops, occupied tracks, etc. Mandated by the Rail Safety Improvement Act of 2008 (RSIA 2008).
	Interoperable Train Control (ITC) is the most common form is the US. It is used on every track in Michigan except part of the Amtrak Michigan Line (AML) (to my knowledge), which uses ITCS (Incremental Train Control), developed in the 1990s by GE Transportation before the RSIA 2008, requiring PTC be installed on most lines, specifically to run the Wolverine and Blue Water locomotives at speeds of 110 MPH on that line. To my knowledge, no one has created software to decode ITCS.

## What is an SDR? Which should I buy?

### What is it?

An SDR (Software-Defined Radio) is basically a scanner radio that plugs directly into your computer. Essentially, you just plug it in, extend the antenna to an appropriate length, and listen to practically anything on the radio waves. It *is* legal without a HAM radio license, as you cannot talk on the frequencies. Some SDRs *do* have broadcast capabilities, so be careful when choosing and using your SDR.

### Which to buy?

By personal opinion, the [Nooelec NESDR SMArt v5 Kit ($54.95 at Amazon)](https://www.amazon.com/dp/B01GDN1T4S) is the best bang-for-buck option readily available on the market.

## About ITCMon and its ancestors

Before the FCC vacated the 900 MHz spectrum in September 2025, Advanced Train Control System (ATCS) (invented 1980s) replaced copper lines to change signals and switches. ATCSMonitor (released 1999, last updated circa 2014) is a software that used those unencrypted frequencies to show a makeshift, dispatcher-style display.

Then, in September 2025, the FCC mandated a vacation of the 900 MHz spectrum used for ATCS to use for cellular communications. Now ATCS is gone in the US for the most part. Some areas still are covered, but that won't last long.
