# Session 1

1. Introductions
  - Presentation of the objectives of the course
  - Group introduction with [Miro board](https://miro.com/app/board/uXjVNHP4YJ4=/?share_link_id=296534171667)

2. [Lecture](../lectures/1-intro-to-ml.md): Introduction to Machine Learning
  - basic concepts & categories of models
  - [MediaPipe demos](https://mediapipe-studio.webapps.google.com/home)
  - inspirations: video + sound

3. First steps: Teachable Machine
  - train an image classifier (classes: emotions)
  - train an audio classifier (classes: colours)

4. Setup of tools

5. Prototyping - Video Classifiers
  - introduction to Transfer Learning
  - use MobileNet + ml5 to classify images. Outputs: (a) labels
  - classify emotions with custom Teachable Machine model + ml5.
  Outputs: (a) labels (b) emojis
  - classify sounds with custom Teachable Machine model + ml5.
  Outputs: (a) labels

6. Prototyping - Video Tracking
  - track face with MediaPipe Face Landmark Detection or Facemesh.
  Output: (a) mesh (b) paint with face - see [mesh map](https://github.com/tensorflow/tfjs-models/blob/master/face-landmarks-detection/mesh_map.jpg)
