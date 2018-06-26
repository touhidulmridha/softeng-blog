---
layout: post
title:  "Securing secrets of an Open Source Application"
breadcrumb: true
author: rahul_verma
date: 2018-07-01
categories: rahul_Verma
tags:
    - Spring
    - Spring Boot
    - Java
    - Vault
    - Hashicorp Vault
    - Open source
teaser:
    info: Your application should not be open but your source code can (should) be
    image: rahul_verma/secure.jpg
header:
    version: small
    title: Software Engineering Blog
    image: header-logo-crop.png
    icon: icon-blog
---

<image src="{{ site.urlimg }}/rahul_verma/open-and-secure.png" />

# Introduction

At OICR, one of [our](http://softeng.oicr.on.ca/team/) core values is to build [open source components](https://github.com/overture-stack) to help science move forward. However, a lot of these components are used to provide controlled access to genomics data. Hence, open-ness and security are the two most fundamental things in [Overture stack](https://overture.bio/)

This post describes how we use [Hashicorp's Vault](https://www.vaultproject.io/) to securely store application secrets for our open source applications. I'll use one of our Spring Boot projects: [overture-stack/EGO](http://www.overture.bio/products/ego) here as a reference. However; same principles can be applied to other technologies as well using corresponding [Vault libraries](https://www.vaultproject.io/api/libraries.html).

### tl;dr

- 1
- 2
- 3

### What is vault...
