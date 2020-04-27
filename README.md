# SK
Contact Tracing - Slovakia

**Covid19 ZostanZdravy** developed by Slovak volunteers/experts (in partnership also with Sygic) for the Slovak National Health Information Centre (state-funded organization founded by the Ministry of Health of the Slovak Republic).

Centralized solution that relies on Bluetooth/BLE (proximity tracing) + GPS location. When there is an interaction with another peer > 15 minutes, the app submits GPS location + peer ID to the server.

Play Store | https://play.google.com/store/apps/details?id=sk.nczi.covid19
-----------|--------------------------------------------------------------
Sources | Unreleased
Website | https://www.old.korona.gov.sk/en/COVID19-ZostanZdravy.php

- APKLAB Analysis

Build | Link
------|-----
1.0.2-sk #3 | https://apklab.io/apk.html?hash=1ff543b3957624e690f3cbf88979640dbd1d1ba03ec36412f081f8dcddf7881c

- JoeSandbox Report

Build | Link
------|-----
1.0.2-sk #3 | https://www.joesandbox.com/analysis/225535/0/html

_**Notice :** There is a new build 1.1.0-sk - released on April 26. It includes bugfixes for BT detection & offline app management. Former builds are indeed quite buggy/crashy. However, latest build 1.1.0-sk hasn't been fully checked, because of issues with the sample retrieved from the Google Play Store._ 

\
Moreover, most of the code of Covid19 ZostanZdravy has been taken from that of **ZostanZdravy**, another application already published on the Play Store since March.

ZostanZdravy already includes proximity tracing & device location, and - above all - it doesn't have same bugs of sister-app. However, it isn't compatibile with EPDB guidelines for contact-tracing apps. Even though with an approx. range, it shows anyway those areas with the users, that have been confirmed as infected by the National Health Auhorities (and have to stay in quarantine).

Play Store | https://play.google.com/store/apps/details?id=sk.marekgogol.zostanzdravy
-----------|-------------------------------------------------------------------------
Sources | Unreleased
Website | https://www.zostanzdravy.sk/

- APKLAB Analysis

Build | Link
------|-----
1.0.4 #6 | https://apklab.io/apk.html?hash=73c84ac26c26d7dc61aa9845838eba23a06f609925fe3e9aa60316c87e8f8c83

- JoeSandbox Report

Build | Link
------|-----
1.0.4 #6 | https://www.joesandbox.com/analysis/225717/0/html 
