---
layout: post
title: Linux Package Management Cheatsheet - Part 1 - Dpkg vs Rpm
published: false
author: PS
categories:
tags:
---

|dpkg|rpm|
|----|---|
|dpkg -l|rpm -qa|
|dpkg -L|rpm -ql|
|dpkg -S|rpm -qf|
|dpkg -p|rpm -qpR|

rpm -qa docker-io
rpm -qal docker-io
rpm -qaR docker-io
rpm -qf docker-io
rpm -qf /usr/bin/docker
