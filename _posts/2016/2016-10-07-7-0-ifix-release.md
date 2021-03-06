---
title: MobileFirst Platform Foundation iFix 7.0.0.0-MFPF-IF201609291531 released
date: 2016-10-07
version:
- 7.0
tags:
- MobileFirst_Foundation
- Announcement
- iFix_7.0
author:
  name: Idan Adar 
---
A new iFix has been released for MobileFirst Platform Foundation 7.0.  
[Download iFix](http://www.ibm.com/support/fixcentral/swg/quickorder?parent=ibm%7EOther%2Bsoftware&product=ibm/Other+software/IBM+MobileFirst+Platform+Foundation&release=7.0.0.0&platform=All&function=all&source=fc) (requires login to IBM Fix Central)

## Highlights
* Fix JSONStore support in Android N
* Fix for SSL keystore information leakage
* Support for Android API level 23

## Included changes in this iFix
*For a cumulative list of all previous fixes, see the iFix download page on IBM Fix Central.*

PI69749 AFTER APPLYING A MFPF PRODUCT UPDATE, EXISTING APP MAY NOT BE ABLE TO OPEN JSONSTORE  
PI69662 NTLM AUTHENTICATION MAY FAIL UNDER LOAD  
PI69380 SSL THREAD INFORMATION NOT CLEARED AFTER ADAPTER CALL, RESULTING IN A CERTIFICATE CHAINING ERROR.  
PI69110 NOT GETTING NOTIFICATION ON 10.0, IF MINAPPOSVERSION IS 9.3  
PI68801 ANDROID APPS THE USE PROGUARD FEATURE WILL NOT WORK.  
PI67404 IOS 8.2 ALERT BOX CANNOT SCROLL  
PI67242 PUSH NOTIFICATION WONT SENT IN ANDROID DEVICES GCM WHEN MAX QUEUE LENGTH IS HIT  
PI66998 ATTEMPTING TO DO AN HTTP GET ON A DIRECTORY FROM THE MOBILEFIRST SERVER MAY REVEAL SERVER CONFIG INFORMATION  
PI66883 JSONSTORE FAILS AND PRODUCES CLIENT ERRORS IN APPLICATIONS RUNNING ON ANDROID N  
PI64093 APPS ON ANDROID VERSIONS 4.4.2 AND EARLIER CANNOT CONNECT TO SERVER USING HTTPS IF ONLY TLS 1.2 IS ENABLED  
PI63245 SERVER LOG SHOWS NPE IN `APPLICATIONSERVICE.__CREATE__`  
PI61438 SENSITIVE SSL KEYSTORE INFORMATION MAY BE DISPLAYED IN CLIENT AND SERVER ERROR LOGS  
PI61332 ANDROID API LEVEL 23 IS NOT SUPPORTED BY MOBILEFIRST PLATFORM FOUNDATION  
PI58939 "SHOWALLNOTIFICATIONSINTRAY" PROPERTY IS NOT PART OF WLCLIENT.PROPERTIES TEMPLATE. THIS IS NOT DOCUMENTED AS WELL.  
PI55920 ATTEMPTING TO SUBSCRIBE TO AN EVENTSOURCE FAILS DUE TO A SQL ERROR  
