---
title: Iridient X-Transformer 1.0.1 Adds Support for Fujifilm X-H1, X-A5, and X-A20
author: mrtmsadmin
type: post
date: 2018-03-09T09:16:34+00:00
url: /2018/03/iridient-x-transformer-1-0-1-adds-support-for-fujifilm-x-h1-x-a5-and-x-a20/
thumbnail: https://www.mirrorlesstimes.com/wp-content/uploads/2018/03/iridient-Digital-Fujifilm.jpg
categories:
tags:
  - APS-c
  - Camera
  - Fujifilm Mirrorless
  - Fujifilm X-A5
  - Fujifilm X-H1
  - Software

---
Iridient X-Transformer 1.0.1 released with support for [Fujifilm X-H1][1], X-A5, and X-A20 mirrorless cameras.

Iridient Digital&#8217;s high quality RAW processing algorithms. This program converts Fujifilm&#8217;s proprietary RAF image data to the openly specified DNG image format.

See the improvements and bug fixes. below. <!--more-->

## Iridient X-Transformer 1.0.1 Adds Fujifilm X-H1, X-A5, and X-A20 Support

  * New Features: 
      * Support added for the Fujifilm X-H1.
      * Support added for the [Fujifilm X-A5][2].
      * Support added for the Fujifilm X-A20.
      * New option added to override the camera make metadata in addition to the model. Can allow for better support of DNG files in software that may unnecessarily prevent loading or may omit features based on the DNG make and model information.
  * Improvements: 
      * Updated camera calibration and profile information for models newly supported in Adobe’s latest DNG Converter 10.2 update (X-H1, X-A5, X-A20).
      * Options to turn off Lightroom color and luminance noise reduction should less agressive in there impact on Lightroom adjustments, particularly with both of these options disabled.
      * Updated to the latest version of Intel’s IPP library (2018u1).
      * Updated to the latest version of the libjpeg-turbo library (1.5.3).
      * Updated to the latest version of the LibreSSL library (2.6.4).
  * Bug Fixes: 
      * Made further attempts to address macOS specific issues specific to the Lightroom plug-in where loading images located on some NAS drives using non-Mac native file systems (NTFS, ext4, etc) may fail.
      * Fixed issue where baseline noise and baseline sharpness metadata was being included even with these options set to “Do Not Include”.

You can download the latest version <a href="http://iridient.com/products/xtransformer_download.html" target="_blank" rel="noopener">here</a>.

Read more [Fujifilm Mirrorless][3] news and <a href="https://www.dailycameranews.com/tag/fujifilm-rumors/" target="_blank" rel="noopener">Fujifilm Rumors</a>.

 [1]: https://www.mirrorlesstimes.com/tags/fujifilm-x-h1/
 [2]: https://www.mirrorlesstimes.com/tags/fujifilm-x-a5/
 [3]: https://www.mirrorlesstimes.com/tags/fujifilm-mirrorless/