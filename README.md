# mediaLab4

This lab aims to build your first WebRTC app.

Choosen to implement Option B + some additional features
Added features:
  - Added face detector for WebRTC
  - Added three new filters: Saturate, Hue-rotate and Contrast
  - Fixed snapshot button (it stops working if you add Tracking.js features)
  - Minor design changes
  - Tested with Google Chrome (version: 73.0.3683.86) and Firefox browsers.

Photos:
![Window](https://www.part.lt/img/0bc5e7d4e1996c33646fb93c0e7d55a3270.png)
![Filters](https://www.part.lt/img/639c42ee4ded51b62a6b7420e98103fb628.png)

There are many open source alternatives to build a simple communication application like Skype. One of the web based solution is WebRTC. You can try a huge set of examples: 
https://webrtc.github.io/samples/

# Requirements for repository
  - You have to clone this repository and make two branches (master and develop).
  - The develop branch should contain commits of every new feature of the AR application.
  - When all features will be ready you have to merge the development branch to the master.

# Requirements for WebRTC application
There are three options to choose from. 

Option A:
  - Use WebRTC filter application code (https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/filter) and additional filter like Canny Edge filter or any other non existing in the sample.
  - It is also needed to add a slider to control a threshold/gain for your filter. It should work realtime.  

Option B:
  - Use WebRTC filter application code (https://github.com/webrtc/samples/tree/gh-pages/src/content/getusermedia/filter) and add face detector. Tracking.js is good place to start (https://trackingjs.com/examples/face_camera.html).

Option C:
  - It is your chance to show your skills and creativity.
  - You can add extra features to existing WebRTC examples.
  - Or anything other.
  
The general requirements for option A, B & C:
  - Test application on at least two browsers and specify in README.md which version and browser it was.
  - To pass this lab, you have to fully complete an option.  
  
# Important notes
  - SSL server is needed to run this lab material.
  - You will be needed to generate self signed sertificate and set up your web server. 
You can try to use these file servers:  
  - Apache: https://www.raspberrypi.org/documentation/remote-access/web-server/apache.md 
  - Tomcat: http://androidsrc.net/installing-tomcat8-raspberry-pi-3/ 
  - HFS: http://www.rejetto.com/hfs/ or any other server.
Proxy http to https:
  - https://technique.arscenic.org/lamp-linux-apache-mysql-php/apache-le-serveur-http/modules-complementaires/article/installer-et-configurer-le-module-ssl-pour-apache2?fbclid=IwAR1_nXNQlrMIdJ5tilVUyr45xeiA91yw21vhnMxWHnuvY01VTd2FVR_T2ao  