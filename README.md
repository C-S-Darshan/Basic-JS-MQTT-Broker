MQTT Broker & Web Client
This project sets up an MQTT broker using Aedes and a simple web client to subscribe to MQTT topics and display messages.

Packages Used
Aedes: MQTT broker
mqtt.js: MQTT client for WebSockets
websocket-stream: WebSocket server integration

Requirements
Node.js: Ensure that Node.js is installed on your system.

Setup
1. Clone the repository
git clone https://github.com/C-S-Darshan/Basic-JS-MQTT-Broker.git
cd Basic-JS-MQTT-Broker

2. Install dependencies (if not already included)
If the project does not include the node_modules folder, run the following command to install the dependencies:
npm install aedes mqtt websocket-stream

3. Run the MQTT broker
node broker.js

4. Open the web client
Open client.html in a web browser.
