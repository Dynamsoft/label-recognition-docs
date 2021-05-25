---
layout: default-layout
title: Dynamsoft Label Recognition Introduction - Overview
description: This is the overview page of Dynamsoft Label Recognition Introduction.
keywords: overview
needAutoGenerateSidebar: true
needGenerateH3Content: true
---

# Overview of Dynamsoft Label Recognition

Dynamsoft Label Recognition (DLR) is an SDK designed to recognize meaningful zonal text or symbols in an image (Label). Common scenarios include price tags in supermarkets, inventory labels in warehouses, VIN codes on car windshield, driver licenses and ID cards, etc. DLR enables you to efficiently read alphanumeric characters and standard symbols from image files, videos regardless of background colour, text colour, font or size. With our SDK, you can create customizable text detection and recognition software with enterprise-grade performance to meet your business needs.


## Key Features

### Extract and Recognize Characters and Symbols
DLR is capable of reading of alphanumeric characters and standard symbols, including period, commas, and dashes, of varying colours, font sizes and styles.

### Various ways to Specify the target zones.
DLR allows you to set the target zones in multiple ways, including manually specified, refer to barcode region, special background region or other text zones.

### Sophisticated Image Pre-Processing Algorithms
For images in low quality, sophisticated algorithms built into DLR SDK are applied to improve contrast, remove noise, and more. The characteristics of texts can also be used to improve the image quality.

### Regular Expression to Improve Accuracy and Robustness
Developers can use Regular Expression to filter the results of DLR. The semantics of a Regular Expression, to specify alphanumeric values that are expected to be scanned, filter unwanted alphanumeric values, improvde the accuracy of DLR results.


## Usage scenarios

### [VIN Scanning]({{ site.docFullPath }}/use-cases/#VinScan)
### [Retail]({{ site.docFullPath }}/use-cases/#Retail)
### [Inventory and Warehouse Management]({{ site.docFullPath }}/use-cases/#Inventory)
### [ID Cards in Air Travel]({{ site.docFullPath }}/use-cases/#IDCards)
### [Lot No. on Drug Bottles in Healthcare]({{ site.docFullPath }}/use-cases/#Healthcare)
### [Parts Tracking and Maintenance]({{ site.docFullPath }}/use-cases/#Tracking)
### [Parcel Labels in Transport and Logistics]({{ site.docFullPath }}/use-cases/#Transport)
### [Voucher Code Scanning]({{ site.docFullPath }}/use-cases/#Voucher)
### [Automatic Data Extraction]({{ site.docFullPath }}/use-cases/#Automatic)
### [Checks in Banking]({{ site.docFullPath }}/use-cases/#Banking)

## Programming Language

Cross-platform application development is now the new trend. The core of DLR is written in C/C++ for performance. The library is also wrapped for use with .NET, Java and other programming languages so that your users can use the functionality on iOS, Android, Windows and Linux. Below is a list of supported OS and programming languages: 

| OS            | Programming Language |
|---------------|----------------------|
|Windows        | C/C++/C\#/VB.NET     |
|Linux          | C/C++                |
|Android        | Java                 |
|iOS            | Swift/Objective-C    |