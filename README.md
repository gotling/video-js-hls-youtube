# Video.JS
## HLS, Youtube and ADs

#### Run demo server
``` sh
npm install
node app.js
```

### ads-hls-youtube.html
Open `http://localhost:8080/ads-hls-youtube.html` in a browser.

Demonstrate problem with showing midroll ads in HLS and Youtube videos.

### hls-techOrder.html
Open `http://localhost:8080/hls-techOrder.html` in a browser.

Demonstrate problem if techOrder is set and trying to play HLS stream

Solved by adding a tech "hls" first in techOrder. 
