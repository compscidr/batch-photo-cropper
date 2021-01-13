# batch-photo-cropper
identifies a photo in a picture and crops the background away

## The Plan
- Label some sample images of photos against the dark background
- Train a yolo model to recognize photos against the dark background
- Run inference on full dataset
- Crop to the bounding box identified for each image
- Write output images to out an output folder

## Resources:
- https://towardsdatascience.com/how-to-train-a-custom-object-detection-model-with-yolo-v5-917e9ce13208
