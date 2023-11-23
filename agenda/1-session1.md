# Session 1

1. Introductions
  - Presentation of the objectives of the course
  - Group introduction

2. [Lecture](../lectures/1-intro-to-ml.md): Introduction to Machine Learning

  - basic concepts & categories of models
  - [MediaPipe demos](https://mediapipe-studio.webapps.google.com/home)
  - inspirations: video + sound

3. First steps: Teachable Machine

  - train an image classifier (classes: emotions)
  - train an audio classifier (classes: colours)

4. Setup of tools

5. Prototyping - Video Classifiers

  - use MobileNet + ml5 to classify images. Outputs: (a) labels
  - introduction Transfer Learning
  - classify emotions with custom Teachable Machine model + ml5.
  Outputs: (a) labels (b) emojis
  - classify sounds with custom Teachable Machine model + ml5.
  Outputs: (a) labels (b) colours

6. Prototyping - Video Tracking

  - track face with MediaPipe Face Landmark Detection or Facemesh.
  Output: (a) mesh (b) paint with face

7. Study on workflow

  - drawing of workflow
  - demos:
    - combining models: [Cassify rock paper scissors ml5.js](https://editor.p5js.org/tlsaeger/sketches/xL2DrkcEb)
    - regression:
      - [Musical mouse](https://editor.p5js.org/ml5/sketches/NeuralNetwork_musical_mouse)
      - [Feature extractor image regresssion](https://editor.p5js.org/ml5/sketches/FeatureExtractor_Image_Regression)
    - chaining tools: [FaceOSC > Wekinator > Processing](https://vimeo.com/175947130)
  - discussion: inputs/outputs (Arduino, MaxMSP / Pure Data, ...)
