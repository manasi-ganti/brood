# brood (brewed)
inspired by imissmycafe.com. 

LIVE WEBSITE AT https://manasi-ganti.github.io/brood/
(note: music/images take a couple seconds to load)

current features:
ambient noise, two coffee shop backgrounds, music (including input for custom music)  

updates:  
input for custom music added  
more music options added, randomly chosen based on genre when drink name is clicked (that means if you don't like the music, click the 'drink' again and it will reset)

features to come (eventually):
mobile friendly, more coffee shop backgrounds, more ambient noise options, maybe a pomodoro timer.

## Instructions to run locally
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