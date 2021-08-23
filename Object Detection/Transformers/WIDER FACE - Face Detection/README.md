# Face Detection on WIDER Face Dataset using Transformers


## Dataset Link
- [Training Set](https://drive.google.com/file/d/0B6eKvaijfFUDQUUwd21EckhUbWs/view?usp=sharing)
- [Validation Set](https://drive.google.com/file/d/0B6eKvaijfFUDd3dIRmpvSk8tLUk/view?usp=sharing)
- [Annotations](http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/support/bbx_annotation/wider_face_split.zip)

## File Structure in Drive after Downloading Dataset
```
- Wider Face
  - dataset
    - wider_face_split.zip
    - WIDER_val.zip
    - WIDER_train.zip
  - detr (clone from this repo)
  - output_images
```

## To Train and Test the Model
clone [this github directory](https://github.com/amanjain487/learning_CV/tree/main/Object%20Detection/Transformers/WIDER%20FACE%20-%20Face%20Detection)
1. Mount Drive
2. Download Dataset from above links and save them in dataset directory
3. Download weights from [this link]()
4. Upload/Save the weights in the following path
```
Wider Face/detr/weights/weights_file.pth
```
6. Run the Colab File
  - Unzip Dataset
  - Separate annotations
  - Train the model
  - Test the model
7. Output Images are saved in output_images directory

## Test Results

