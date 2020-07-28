# Abstract
Open containers, i.e., containers without covers, are an important and ubiquitous class of objects in human life. In this letter, we propose a novel method for robots to "imagine" the open containability affordance of an unknown object via physical simulations. We implement our imagination method on a UR5 manipulator. The robot autonomously scans the object with an RGB-D camera. The scanned 3D model is used for open containability imagination which quantifies the open containability affordance of an object. This quantification is used for open container vs. non-open container binary classification. If the object is classified as an open container, the robot further imagines pouring into the object to obtain the pouring position and orientation for real robot autonomous pouring. We evaluate our method on open container classification and autonomous pouring of granular contents on a dataset containing 130 unknown real-world objects with 57 object categories. Although our proposed method uses only 11 objects for simulation calibration (training), its container classification aligns well with human judgements. In addition, our method endows the robot with the capability to autonomously pour into the 55 containers in the dataset with a very hight success rate. We also compare to a deep learning method. Results show that our method achieves the same performance as the deep learning method on open container classification and outperforms it on autonomous pouring.

# Open Containability Imagination Demo
 

# Autonomous Pouring Demo

### 1. Candlestick (Detailed with explanations)
{% include youtubePlayer.html id="mfr69KGa_W0" %}

### 2. Mug
{% include youtubePlayer.html id="blZZeJ2g-90" %}

### 3. Gravy Boat

### 4. Baking Cup

### 5. Origami Cup

### 6. Wooden Bowl

### 7. Basket

### 8. Ash Tray

### 9. Soap Dish

### 10. Plate

### 11. Chef Hat

### 12. Cup
