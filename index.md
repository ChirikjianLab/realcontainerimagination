# Abstract
Open containers, i.e., containers without covers, are an important and ubiquitous class of objects in human life. In this work, we propose a novel method for robots to "imagine" the open containability affordance of an unknown object via physical simulations. We implement our imagination method on a UR5 manipulator. The robot autonomously scans the object with an RGB-D camera. The scanned 3D model is used for open containability imagination which quantifies the open containability affordance of an object. This quantification is used for open container vs. non-open container binary classification. If the object is classified as an open container, the robot further imagines pouring into the object to obtain the pouring position and orientation for real robot autonomous pouring. We evaluate our method on open container classification and autonomous pouring of granular contents on a dataset containing 130 unknown real-world objects with 57 object categories. Although our proposed method uses only 11 objects for simulation calibration (training), its container classification aligns well with human judgements. In addition, our method endows the robot with the capability to autonomously pour into the 55 containers in the dataset with a very hight success rate.

# Introductory Video


# Open Containability Imagination Demo

The simulation videos are outputed from the Pybullet visualization. The time for the simulation is in terms of the video duration, i.e., 8x means video playing in 8x speed. The reported duration for open containability imagination in the paper is evaluated without visualization.

### 1. Gravy Boat (Detailed with explanations)
#### Labeled as open container
<iframe width="800" height="450" src="https://www.youtube.com/embed/U5a4fG1ptfA" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 2. Chef Hat
#### Labeled as open container
<iframe width="800" height="450" src="https://www.youtube.com/embed/y-YYY_bs_Ps" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 3. Book
#### Labeled as non-open container
<iframe width="800" height="450" src="https://www.youtube.com/embed/zGaItrrFKts" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

# Autonomous Pouring Demo

The simulation videos are outputed from the Pybullet visualization. The time for the simulation is in terms of the video duration, i.e., 8x means video playing in 8x speed. The reported duration for open containability imagination and pouring imagination in the paper is evaluated without visualization.

### 1. Candlestick (Detailed with explanations)
<iframe width="800" height="450" src="https://www.youtube.com/embed/mfr69KGa_W0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### 2. Mug
<iframe width="800" height="450" src="https://www.youtube.com/embed/blZZeJ2g-90" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

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
