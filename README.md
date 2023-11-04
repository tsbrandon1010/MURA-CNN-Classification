# Skeletal Abnormality Detection Using CNN

Training a Convolutional Neural Network to solve [Stanford's MURA competition](https://stanfordmlgroup.github.io/competitions/mura/).

## Part 1: Training a Model on Wrist X-Rays

**Below is an example of images labeled as "abnormal" and "normal":** <br>
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/6ec3f79c-461d-402b-8f6d-526eab175975)

**In analyzing the data, there appeard to be some inconsistant data, or data that contained ceratin "edge" cases:** <br>
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/3c5c063b-908d-4b7c-8dc0-9cfbe8e6a92c)

**The data was split as follows:** <br>
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/5cb9389d-4782-41d3-beeb-271053f0e692)

### The Model:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/0b4e87c2-329a-4b49-b37d-c5a27d694532)

### Training:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/9ecf55d0-65ac-4d3a-b1b3-f294b8980aeb)
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/8984baa5-b8a3-49f8-95f0-d623f03791dd)

### Overfitting Analysis and Results:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/aeceb9f9-fcc7-4c57-bfb8-66975b38536d)

### Results Compared to Stanford's Model and Doctors:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/675cd711-b3e1-491b-b1b8-b68cd59c4d9d)

### Testing The Wrist Trained Model on All Body Parts:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/799fa65d-0514-4ab2-8352-67c5fabea704)

## Part 2: Training a Model on All Body Parts
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/9fe37259-b7bb-4812-8d02-8990bba77da9)

### Training:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/27c5d942-c99d-4738-80f0-a1de365496e6)
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/dbdc2d9c-3a31-48d9-a317-e48081a343e5)

### Overfitting Analysis and Results:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/224b7028-1cb7-480e-b6e1-80547d40ed66)

### Results Compared to Stanford's Model and Doctors:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/1ca30b05-8992-4796-9a35-9991bc0570d1)

### Class Activation Map of The Model:
![image](https://github.com/tsbrandon1010/MURA-CNN-Classification/assets/15933213/88a40a7c-acd6-45d1-8260-19a5ba525d38)
