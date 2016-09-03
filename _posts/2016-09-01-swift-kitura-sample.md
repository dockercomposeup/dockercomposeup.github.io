---
layout: post
title: Swift on the Server with IBM Kitura
caption: Start experimenting with Swift on the server by running the IBM Kitura Sample.
date: 2016-09-01 00:00:00 -0500
image: '/assets/img/'
main-class: 'swift'
tags:
- swift
- ibm
- kitura
gitrepo: https://github.com/markwatsonatx/tutorial-swift-kitura-sample
gitfolder: tutorial-swift-kitura-sample
---

### Ports and URLs

| Name | Port | URL |
| ------ | ---- | --- |
| Kitura Sample | 38090 | <a href="http://127.0.0.1:38090">http://127.0.0.1:38090</a> |

### Description

Run and experiment with the [IBM Swift Kitura Sample](https://github.com/IBM-Swift/Kitura-Sample) in Docker.

The local src folder will be mapped to the Docker container.
Changes to the code in the src folder will be monitored by the Docker process, re-compiled, and the HTTP server will be restarted.