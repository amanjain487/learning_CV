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
|Output Images|Output Images|
|-------------|-------------|
|![0_Parade_marchingband_1_149](https://user-images.githubusercontent.com/46129975/130428899-f0b99109-b3cf-4dc1-8c24-1a6efcf732bb.jpg)|![0_Parade_marchingband_1_156](https://user-images.githubusercontent.com/46129975/130428933-c59eed74-fc9f-4bcf-8f72-b1c45848ea71.jpg)|
|![1_Handshaking_Handshaking_1_94](https://user-images.githubusercontent.com/46129975/130428945-6bb40cd7-c962-4de0-9e52-eedbe0bf4c36.jpg)|![1_Handshaking_Handshaking_1_762](https://user-images.githubusercontent.com/46129975/130428958-b17e73ed-4e7a-4055-9185-e32ffba90c45.jpg)|
|![1_Handshaking_Handshaking_1_766](https://user-images.githubusercontent.com/46129975/130428968-3245938d-ee40-40d9-9312-baa0f82df7d9.jpg)|![1_Handshaking_Handshaking_1_781](https://user-images.githubusercontent.com/46129975/130428976-dd7898e0-8c63-4ceb-8334-2a1964f9197f.jpg)|
|![1_Handshaking_Handshaking_1_801](https://user-images.githubusercontent.com/46129975/130428987-d5eb128e-14ef-4279-84d3-6a841871489d.jpg)|![1_Handshaking_Handshaking_1_827](https://user-images.githubusercontent.com/46129975/130428994-0b774f8b-d7d8-41e7-ae55-287904f2eb6f.jpg)|


