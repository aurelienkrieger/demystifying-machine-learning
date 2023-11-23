# Demos

1. Video classifier / Teachable Machine

Use Teachable Machine web interface to train and test a classifier on video feed.

2. Audio classifier / Teachable Machine

Use Teachable Machine web interface to train and test a classifier on audio feed.

3. Image classifier / ml5js

Use MobileNet model & `ml5.imageClassifier()` to do image classification with ml5js / p5.js.
Outputs:
  - raw labels

4. Custom video classifier / Teachable machine + ml5js

Import Teachable Machine custom classifier to do image classification with ml5js / p5.js.
Outputs:
  - raw labels
  - emojis

5. Sound classifier / ml5js

Use SpeechCommands18w model `ml5.soundClassifier()` to do image classification with ml5js / p5.js.
Outputs:
  - raw labels

6. Custom sound classifier / Teachable machine + ml5js

Import Teachable Machine custom classifier to do sound classification with ml5js / p5.js.
Outputs:
  - raw labels
  - emojis

7. Facial tracking / ml5js

Use Facemesh model with `ml5.facemesh()` to do face tracking with ml5js / p5.js.
Outputs:
  - raw data points
  - draw with face

8. Emotions tracking / Teachable machine + ml5js

Import Teachable Machine custom classifier to do emotions classification with ml5js / p5.js.
Outputs:
  - emojis

9. Emotions tracking / FaceOSC + Wekinator

Extract face features with faceOSC and use Wekinator to train custom emotions classifier and send classes over OSC.
Outputs:
  - emojis (p5.js / Processing)
  - sounds (PureData)

10. Object detection / ml5js

Use COCO / YOLO models to with `ml5.objectDetector()` to do object detection with ml5js / p5.js.
Outputs:
  - classes
  - bounding boxes
