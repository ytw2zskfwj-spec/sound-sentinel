# Sound Sentinel

A free web app that listens for important sounds and alerts deaf and
hard-of-hearing users with full-screen flashes, tones, and live captions.

## Features
- Recognizes smoke alarms, sirens, doorbells, knocks, baby cries,
  phone rings, dog barks, car horns, and breaking glass
- Teach it your own sounds (beta)
- Live captions that highlight your name
- Bedside mode for overnight use
- Works offline after the first load; audio is processed on the device
  and never uploaded

## Try it
Open the live app: https://ADAMsScienceproject.github.io/sound-sentinel
On iPhone, tap Share, then Add to Home Screen.

## Built with
TensorFlow.js, Google's YAMNet sound model, and the Web Speech API.

## Limitations
Sound Sentinel is a helper, not a replacement for certified smoke or
carbon monoxide alarms. It listens only while the app is open and the
screen is on. iPhone web apps cannot vibrate.
