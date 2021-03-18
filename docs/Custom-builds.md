# Custom Builds

We pre-build CompreFace with different models for the face services, so you can choose the best build for your purposes. Some of them have higher accuracy but the performance on CPU is low, others optimized for low-performance hardware and have acceptable accuracy.
Default CompreFace docker-compose build includes FaceNet library for face recognition and custom age and gender detector and doesn’t include GPU support.
You can find custom builds in the “builds” folder. There is more information about builds and installation instructions in the readme in this folder. 