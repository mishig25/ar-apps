# Brain AR
 A small personal project report

###  *The human brain has 100 billion neurons, each neuron connected to 10 thousand other neurons. Sitting on your shoulders is the most complicated object in the known universe.* - Michio Kaku

#### Demo
![Alt Text](https://github.com/mishig25/brainAR/raw/master/result-min.gif)

#### What is this project about?
Visualize brain and its neural activity in Augmented Reality using OpenPose and Unity.

#### Dependencies
* [OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)
* [Unity](https://unity3d.com/)

#### Process steps
1. Extract 2D head position data through OpenPose
![Alt Text](https://github.com/mishig25/brainAR/raw/master/openpose_demo-min.gif)
2. Model, shade, and render 3D brain in Unity
![Alt Text](https://github.com/mishig25/brainAR/raw/master/brain_unity-min.gif)
3. Interpret 2D head position data retrieved in Step1 in Unity, reconstruct 3D head position data from 2D data
![Alt Text](https://github.com/mishig25/brainAR/raw/master/unityOpenpose-min.gif)
4. Find optimal transformations matrices so that transformations of 3D brain model would much as accurately as possible transformations of 3D head position data from Step3
![Alt Text](https://github.com/mishig25/brainAR/raw/master/result-min.gif)
