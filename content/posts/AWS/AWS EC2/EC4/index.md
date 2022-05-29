---
title: "Monolithic applications and microservices"
date: 2022-05-16T08:06:25+06:00
description: Messaging and queuing. 
menu:
  sidebar:
    name: Monolithic applications and microservices  
    identifier: mono-micro
    parent: aws-cloud
    weight: 40
tags: ["Basic", "Multi-lingual"]
categories: ["Basic"]
---

## Introduction

Applications are made of multiple components. The components communicate with each other to transmit data, fulfill requests, and keep the application running. 

Suppose that you have an application with tightly coupled components. These components might include databases, servers, the user interface, business logic, and so on. This type of architecture can be considered a monolithic application. 

In this approach to application architecture, if a single component fails, other components fail, and possibly the entire application fails.