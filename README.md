# watson
This project demonstrate Watson Speack to Text (STT) API on NodeRed.
To make a demo environment, Just copy one of the *.json file that fit for your pourpose and import it to your NodeRed Flow.

・　NodeRed-STT.json
HTTP API version of STT. This demo read your recording file and create transcript for all data at once.  The result shows on Freeboard Dashbord.  "freeboard" is pre-request to execute this Demo (*1).
  (https://www.npmjs.com/package/node-red-contrib-freeboard) 
  
・　NodeRed-websocket.json (recomended for demo)
websocket version of STT. This demo shows the time,confidence and transcript of your vice recording files in real-time fashion. 

・　NodeRed-corpus.json:
Create/Add/Delete/List Corpus and Words for custom STT. 

How to install freeboard:
After provisioning NodeRed, 1) Download package.json on your laptop. 2) Add "node-red-contrib-freeboard": "0.*" in that package.json. 3) "cd" to the same directory of that file. 4) Issue "cf push applname".   (for more detail,  https://console.ng.bluemix.net/docs/starters/Node-RED/nodered.html#nodered)
 
