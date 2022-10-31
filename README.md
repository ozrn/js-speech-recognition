# JS30 #20: js-speech-recognition
This project is yet another project of JS30 practices by Wes Bos and it shows how to convert voice to text using Web speech API.
## Installation
Clone this repository with the command below
``` 
git clone https://github.com/ozrn/js-speech-recognition
```
Change directory to the cloned folder
```
cd js-speech-recognition
```
Check whether node and npm have already been installed globally on your machine with the below commands
```
node -v // node version installed on your machine
npm -v //  npm version installed on your machine
```
In this step, install the project dependencies and then start with the following commands
```
npm install
npm start
```
Run the project at http://localhost:3000
### Overview
When the code is run, the browser will ask permission to use your microphone so you will need to give permission.<br> The "result" event of Web speech API will be fired calling a function that gets transcript and returns it as a string, when speech is recognized.<br> Text context of paragraph will be set to transcript and new paragraphs will be added after each break.   


