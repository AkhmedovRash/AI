# AI
'''
This script:
- Optionally loads and preprocesses a specific COCO category with bounding boxes and captions.
- Loads CUB dataset text embeddings and images for conditional image generation.
- Builds a Stage-1 conditional GAN (generator + discriminator) with text embeddings as conditioning.
- Trains the GAN to generate 64x64 images conditioned on text.
- Saves generated samples and trained model weights.

Dependencies:
- TensorFlow / Keras
- PIL, NumPy, Pandas, Matplotlib
- pycocotools (for COCO preprocessing)
'''
