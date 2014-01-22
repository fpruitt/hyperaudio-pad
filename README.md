# Hyperaudio Pad

This is the repository for the Hyperaudio Pad. The Pad makes use of the hyperaudio api in order to display a video and its transcript, as well as provide a space to store time-stamped selections of the video. The Pad can be used to trim a video, easily chop a quote out of a video, or put together video essays. The transcripts that come with this version of the pad are samples to give you a taste of what can be done with this system. For more information, check out [hyperaud.io](http://www.hyperaud.io/).
## Getting Started

### 1) Have a webserver running

* If you already have a web server running on your machine, skip this step.
* If you are on Windows or OSX, download and install a webserver of your choice. If you do not already have a preference, check out [XAMPP](http://www.apachefriends.org/en/xampp.html), a free, fully featured web stack.
* If you are on linux, you probably already have apache installed and running. You can run the following command to see if apache is running:
```
service httpd status
```
If it is off, run
```
service httpd start
```
* On any platform, you can check to see if your webserver is running by navigating your web browser to [localhost](http://localhost/).

### 2) Extract HyperAudio-Pad
* Extract Hyperaudio-Pad in the root of your webserver.
* If you installed XAMPP on Windows, the webserver root is C:\XAMPP\htdocs (by default). On OSX, XAMPP installs in /Applications/XAMPP/htdocs.
* In linux, this varies from flavor to flavor, but the web directory is usually in /etc/httpd or /var/www... You can find it by checking your httpd.conf, usually found at /etc/httpd/conf/httpd.conf or in /usr/local/etc/apache22/httpd.conf. 

### 3) Navigate to the Pad Via Web Browser
* Navigate to the pad by point your web browser at (localhost/hyperaudio-pad)[localhost/hyperaudio-pad] if the folder you extracted in the previous step was called hyperaudio-pad. This should load up a screen with instructions on how to get started.
