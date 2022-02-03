# affirmationbot

A friendly robot that listens and gives affirmations based on your moods.

(Currently only works in Chrome, on desktop.)
**Use the deployed app [here](https://letakeane.github.io/affirmationbot/)!**

## Summary

I was interested in learning something new, and had run across the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) before. It seemed like a fun sandbox to play in!

Over the course of a few hours, I built this very rough draft of a sweet robot who listens to you and gives you affirmations. This was partly motivated by conversations I'd recently had with students, who were feeling down and wrestling with self-doubt.

## Technology

Makes use of

- the Web Speech API
  - primarily speech recognition
  - and speech synthesis tools
- HTML
- very suspicious and inconsistent CSS
- and vanilla JavaScript

Users are greeted by a spoken invitation from the robot to state their mood. The robot listens for the user to speak a set of pre-defined mood words, and responds with an appropriate affirmation, once again synthesizing speech.

## Screenshots

![initial animation](https://i.giphy.com/media/QdykXxviBNQTqMHING/giphy.gif?cid=790b76119f75d0ca730adaf2b80039d3918e0537b603121b&rid=giphy.gif&ct=g)
![initial greeting](https://i.imgur.com/8vHpHN6.png?1)
![affirmation](https://i.imgur.com/IRvSFMd.png)

## Project Status

**Stasis**: This project is not currently being updated, but I do have actual plans to revisit it and make it more readily usable.

To do:
1. Update UI to be responsive for mobile
2. Add in polyfill/shim for Firefox (does not currently support the SpeechRecognition API)
3. Stabilize the default voice (API updates affect the synthesized voice)
4. Allow user to choose robot's voice
5. Possibly implement a connection with Watson's tone analysis API to allow users to speak more naturally to the robot
