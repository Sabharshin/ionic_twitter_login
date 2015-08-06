# ionic_twitter_login
A step by step and working example of twitter login using ionic and ng-cordova-oauth

Pre-requisites<br>
Create a twitter app and get Consumer Key (API Key) and Consumer Secret (API Secret).
<br><br>
Steps<br>
1) Create a project <br>
2) cd into the project<br>
3) Add the required platform(s)<br>
4) Download "ng-cordova.min.js" and add to js folder<br>
5) Add the "ng-cordova.min.js" path in "index.html" file just above "cordova.js" path<br>
6) Add the dependancy "ngCordova" in "app.js" angular module<br>
7) Add the plugin "cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-inappbrowser.git" from terminal<br>
8) Download the "sha1.js" file and add to js folder<br>
9) Add the "sha1.js" path in index file<br>
10) Type bower "install ng-cordova-oauth -S" from terminal<br>
11) Add the "ng-cordova-oauth" file path to index file<br>
12) Include "ngCordovaOauth" dependancy in "app.js" angular module<br>
13) Add the "$cordovaOauth" to the controller which is using twitter login function<br>
14) Add the controller and ng-click in index.html<br>
15) Add the twitter login function in the controller as show in the app.js (Please replace the api_key and api_secret with your twitter app details)<br><br>

Reference:<br>
http://blog.ionic.io/oauth-ionic-ngcordova/<br>
https://github.com/nraboy/ng-cordova-oauth<br>
<br>
Thanks to Nic Raboy for the plugin and blog.
