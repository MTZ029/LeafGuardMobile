LeafGuardMobile
AI-powered mobile app for plant disease detection – bridging agriculture & AI.

Flutter
TensorFlow
FastAPI
License

About LeafGuardMobile
LeafGuardMobile empowers farmers with a simple mobile solution: snap a picture of a leaf, get a disease diagnosis powered by AI.
Leveraging a TensorFlow model trained on the PlantVillage dataset (38 disease classes), the app delivers results fast—even offline using TFLite.

Tech Stack & Highlights
Layer	Technologies & Tools
Mobile (UI)	Flutter (Dart), image_picker, http
ML Model	TensorFlow/Keras → TensorFlow Lite (.tflite)
Backend (Opt.)	FastAPI server with Python & Uvicorn
Dataset	PlantVillage (54K+ images, 38 disease categories)
Core Features	On-device inference, camera/gallery integration, menu-less UI
Privacy & Use	No third-party cloud needed — offline ready
Feature Snapshot
Functionality	Details
Leaf Detection	Use camera or gallery to load a leaf image.
Model Inference	Runs TFLite model on-device or calls API.
Results Display	Shows disease name (and confidence score).
User Flow	Simple tap → diagnose → view result → repeat.
Getting Started
Clone & Run the App
git clone [https://github.com/Uza1rxd/LeafGuardMobile.git](https://github.com/MTZ029/LeafGuardMobile.git)
cd LeafGuardMobile
flutter pub get
flutter run


Contributing

Want to help?

Fork the repo

Create a feature branch (e.g., feature/describe-diseases)

Commit & push your changes

Open a pull request — we’ll review it with gratitude!

Ideas:

Add disease descriptions or remedies

Enhance UI/UX

Boost model accuracy or retraining pipelines

License

Proprietary (All Rights Reserved)
This repo is publicly accessible, but requires written permission from the author for any reuse, modification, or distribution.

LeafGuardMobile — making plant disease diagnosis simple, smart, and accessible. Let's grow better, together.
