# 🫧 Bubble

Blow soap bubbles with your hands through your webcam.

- **Pinch** (thumb and index finger) to blow a bubble. Hold the pinch to make it bigger, then let go to release it.
- **Poke** a bubble with your fingertip to pop it.
- **Touch your fingertips to your thumb in an "O"** and drag to pull a soap-film sheet behind your hand.

## Run it

It's a single static page. Serve the folder and open it in a browser:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

The browser needs camera access. Browsers only allow the camera on `localhost` or over HTTPS.

## Credits

- **Hand tracking:** [MediaPipe Tasks Vision](https://ai.google.dev/edge/mediapipe/solutions/vision/hand_landmarker) (Hand Landmarker) by Google, Apache 2.0.
- **Soap-film shader:** ported from ["Physically-Based Soap Bubble"](https://www.shadertoy.com/view/XtKyRK) by Matteo Mannino on Shadertoy, [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/). Because of that license, this project is for non-commercial use only.
