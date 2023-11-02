---
title: "29.11.2023 - Testcontainers & API Mocking and WINE & MSVC - November Meetup"
summary: Testcontainers & API Mocking and WINE & MSVC
date: 2023-09-15
weight: 2
aliases: ["/november-2023-meetup"]
tags: ["c++", "API", "WireMock", "Containers", "WINE", "MSVC"]
author: "Benny Gaechter"
---


Hi everyone,
The next C++ meetup is happening on Wednesday, November 29 at the tipi.build offices in the Bluelion, Josefstrasse 219 in Zurich.

## Agenda

- Doors open at 18:00
- Talk 1 starts at 18:30
- Short break at 19:20
- Talk 2 at 19:30
- Food & Drinks 🍕 sponsored by tipi.build and Socialising on the roof top (weather permitted) at 20:15
- Closing around 22:00

## General

You would like to be a speaker or suggest someone who would like to join as a speaker, please get in touch with Benny via chat on Meetup.
Looking forward to seeing you all 😃

## Testcontainers and API mocking with WireMock for C/C++ - Oleg Nenashev

Testcontainers has become one of the most popular tools for software integration testing. If you can put your system-under-test into a container, Docker compose cluster or a pod, this is what you're likely to use. If your target isn't ready, not containerizable or just too heavy for testing as is, you can always use API mocking like WireMock to mock your interfaces including REST API, gRPC, etc. But are these tools available to C/C++ developers? And the answer is YES!
In September 2023 I created Testcontainers for C/C++. This is not a standalone Testcontainers engine, but a C-style shared library adapter for native languages like C/C++, and also D, Lua, Swift, etc. It is a MVP SDK that can be later extended for the languages. The project is based on Testcontainers for Go which is one of the most powerful Testcontainers implementations. And yes happy to chat about how it does [and doesn’t] work under the hood.
The objective of this talk is to present the existing solution, find early adopters and get feedback from professional C/C++ developers who use modern C/C++. For me it has been 10 years since I used it professionally for Embedded and SCADA projects, so it would be awesome to get the community feedback on use-cases and priorities!

### About the Speaker

Oleg is a developer tools hacker, community builder and consultant currently working on WireMock and WireMock Cloud ecosystems. He's passionate open source software and open hardware advocate. Oleg is a core maintainer and board member in the Jenkins project where he writes code, mentors contributors and organizes community events. He is a TOC member in the Continuous Delivery Foundation, and also a CDF and CNCF ambassador. Oleg has a PhD degree in electronics design and volunteers in the Free and Open Source Silicon Foundation.

## (Fine) WINE & MSVC - Yannic Staudt, tipi.build

A short story about wine, command line arguments, installers, paths and everything it takes to cross compile binaries for Windows targets on a Linux host using MSVC (and why you might consider doing the same!).

### About the Speaker

Yannic is one of the co-founders of tipi.build, a hacker at heart and has written software for anything from 4 bit micros to distributed parallel data processing systems.

