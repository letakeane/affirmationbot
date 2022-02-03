# affirmationbot

A friendly robot that listens and gives affirmations based on your moods.

Makes use of the Web Speech API, primarily the speech recognition and speech synthesis tools.

Users are greeted by a spoken invitation from the robot to state their mood. The robot listens for the user to speak a set of pre-defined mood words, and responds with an appropriate affirmation, once again synthesizing speech.

Currently only works in Chrome, on desktop.

**Use the deployed app [here](https://letakeane.github.io/affirmationbot/)!**

![initial animation](https://i.giphy.com/media/QdykXxviBNQTqMHING/giphy.gif?cid=790b76119f75d0ca730adaf2b80039d3918e0537b603121b&rid=giphy.gif&ct=g)
![initial greeting](https://i.imgur.com/8vHpHN6.png?1)
![affirmation](https://i.imgur.com/IRvSFMd.png)

## Project Status

To do:

1. Update UI to be responsive for mobile
2. Add in polyfill/shim for Firefox (does not currently support the SpeechRecognition API)
