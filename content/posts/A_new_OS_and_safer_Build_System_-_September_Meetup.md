---
title: "13.09.2023 - A new OS and safer Build System - September Meetup"
summary: A new OS and safer Build System - September Meetup
date: 2023-09-13
weight: 2
aliases: ["/september-meetup"]
tags: ["tipi.build", "bazel", "cmake", "gapfruit", "microkernel", "build system"]
author: "Benny Gaechter"
---


Hi everyone,

The next C++ meetup is happening on Wednesday, September 13 at the tipi.build offices in the Bluelion, Josefstrasse 219 in Zurich.

## Agenda

Doors open at 18:00
Talk 1 starts at 18:30
Short break at 19:15
Talk 2 at 19:30
Talk 3 at 20:00
Pizza 🍕 sponsored by tipi.build and Socialising on the roof top (weather permitted) at 20:30
Closing around 22:00

## General

You would like to be a speaker or suggest someone who would like to join as a speaker, please get in touch with Benny via chat on Meetup.

Looking forward to seeing you all 😃

### Microkernels, Genode and Gapfruit OS - Alice Domage & Timo Nicolai

In this talk we want to give you a brief introduction to the world of microkernel operating systems. Microkernel systems consist of a small trusted kernel and a number of separate userspace components that implement e.g. device drivers. Perhaps the most prominent microkernel today is the fast and mathematically verified seL4 kernel.

When compared with traditional monolithic systems such as Linux, this approach has a number of benefits with regards to reliability and security.

We present common properties of microkernel systems through the lens of the Genode OS framework which is written in C++ and implements a variety of userspace components and libraries with which microkernel systems can be developed in a mostly kernel-agnostic way. Here we talk about topics such as client-server architecture, capability based security, the component hierarchy and the C++ runtime. We also walk through some practical examples.

Last but not least we give an overview of our work at Gapfruit AG where we develop the Genode-based Gapfruit operating system.

### About the speakers

Alice Domage and Timo Nicolai are Operating Systems Engineers at Gapfruit AG, a startup based in Zug. There they work on the Gapfruit OS Microkernel Operating System which is intended to be a reliable and secure alternative to Linux for IoT edge devices. Alice is currently working on the lower level of the Gapfruit software stack, including device drivers and performance tracing while Timo is working on cloud integration and public key infrastructure.

### A short history of build systems

What makes a build system great?

What differentiates various build systems?

Why should you pick a build system vs. another one?

### About the Speaker

Antonio Di Stefano (aka @TheGrizzlyDev) is a DevEx engineer at EngFlow, known for his passion in creating tools that elevate the happiness and productivity of software engineers. He thrives on dissecting and pushing the limits of technology to understand its inner workings. Antonio’s mission is to empower developers with seamless experiences and innovative solutions. He also contributes to natalie the very little spare time he has left from trying to run snake and/or doom on build systems!

Modern CMake for faster and safer C++ builds - Damien Buhl, tipi.build

Today the C++ community is all about safety, the focus is heavy on language features. But build tools are a key to bring safety to C++, we explore how to get today a safer and faster C++ build with modern CMake and tooling.

### About the Speaker

Damien (aka @daminetreg), co-founder and CEO from tipi.build is an enthusiast C++ developer. He is Opensource entrepreneur, CppCon Speaker, GameMaker.fr community founder, Qt for Android contributor and Boost.Fusion maintainer since 2014
