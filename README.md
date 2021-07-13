# brood (brewed)
inspired by imissmycafe.com and lofi.cafe

current features:
ambient noise, two coffee shop backgrounds, music (including input for custom music)

features to come:
skip button and more music options, more coffee shop backgrounds, more ambient noise options, maybe a pomodoro timer, ~~an actual live site would be cool~~. 
YO WE HAVE AN ACTUAL LIVE WEBSITE: https://manasi-ganti.github.io/brood/


## Instructions
### 1. Download
Download the github code as a zip file (and unzip, obviously).  
If you don't want to even touch Terminal/Command line, from here you can just double-click index.html to open it in your browser, but most of the music won't work.


#### 2. Set up local HTTP server.
Open your Terminal app and navigate to the downloaded folder: `cd Downloads/brood-main`. 
Start the HTTP server: `python -m SimpleHTTPServer`. 
(If you have Python 3: `python3 -m http.server`). 
![Image of command line](https://i.imgur.com/JEQ403Z.png)

#### 3. Visit website.
Go to http://localhost:8000/ in your browser. Most of the functionality is pretty straightforward. The videoId is the id of a youtube video (the stuff after "?v=" in the link). 

![Image of web app](https://i.imgur.com/1AVFtZq.png)