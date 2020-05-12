---
template: post
title: Introducing Fleek Storage
slug: Fleek-Storage-Release
draft: true
date: 2020-05-06T04:02:37.816Z
description: >-
    We're excited to release Fleek Storage! Storing files on IPFS is easier and more performant than ever. We've leveraged an already popular S3 interface to interact with IPFS via our easy to use application, CLI, and SDK. The Storage solution comes with a built-in CDN, File Compression, and image resizing to achieve upmost performance.
category: "Announcement"
socialImage: /StorageReleaseCover.png
tags:
  - Announcement
  - Product Release
---

<!--
  TODO BEFORE RELEASING
  Link for tech docs
  Link for talk given at IPFS summit 
--->

![](media/StorageReleaseCover.png)

We're excited to release Fleek Storage! Storing files on IPFS is easier and more performant than ever. We've leveraged an already popular S3 interface to interact with IPFS via our easy to use application, CLI, and SDK. The Storage solution comes with a built-in CDN, File Compression, and image resizing to achieve upmost performance.

# Fleek Storage App

The Fleek app now has a Storage page. If you're already a Fleek user you'll see the new Storage page appear on the left-hand navigation menu of your screen. You can now upload, browse, and manage all your files through the app interface. All files uploaded are published to IPFS and published to DNS, with a CDN and File Compression. You can view and reference the files through the Fleek Storage URL, and can view directly on the IPFS gateway. Since our approach has been to leverage an S3 interface any S3 compatible CLI and SDK will work with Fleek. [Take a look]() at our updated tech docs to learn more about using Storage in-app.


![](media/UploadFolder.gif)


# Fleek Programmable Interfaces

We've release the Fleek CLI, [here's the link](https://www.npmjs.com/package/@fleekhq/fleek-cli) to the npm package manager. To start, the Fleek CLI is to log in and create API keys. Since our interface is S3 compatible, you can use the S3 CLI and APIs to interact with your Fleek storage buckets. The AWS CLI and SDK work with any language that your app is built with, such as JavaScript, Go, C++, Python and Ruby. [Take a look]() at our docs for getting set up with the CLI and integrating storage directly in your app.

# Unveiling at the IPFS Pinning Summit

We first unveiled the storage product during the [IPFS Pinning Summit](https://ipfspinningsummit.com/) event held on the 7th-8th of May 2020. Fleek's COO Brett Shear gave a live demo of the new product which received amazing positive feedback. We're thankful to the organizers who have made this event possible.

Missed the event? No worries! You can [watch a recording]() of the presentation and demo as though you were there!

# Stay Tuned!

Thank you for reading our release updates. Sign up or sign back in and check out the updates for yourself!

* [Sign up](https://app.fleek.co) to try for yourself
* [Join](https://join.slack.com/t/fleek-public/shared_invite/zt-bxna7y1d-PbVdut4rgHt5jM6Zjg9g9A) the #community slack channel
* [Follow](https://twitter.com/FleekHQ) us on Twitter
* [Read](https://docs.fleek.co/) our Tech Docs
* Contact us at support@fleek.co 