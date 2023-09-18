# Efficient High-Resolution Image-to-Image Translation using Multi-Scale Gradient U-Net

This repo provides the code implementation of the paper Efficient High-Resolution Image-to-Image Translation using Multi-Scale Gradient U-Net. More specificallly to train on a specific dataset, include that dataset in the datasets folder.

# Requirements
<ol type="A">
   <li>python 3.6</li>
   <li>Tensorflow  1.12</li>
   <li>Keras</li>
   <li>Cuda toolkit 9.0</li>
   <li>Cudnn</li>
</ol>

# Instructions to run the code
<ol type="1">
   
<li>Download any of the datasets mentioned in the paper
   <a href="https://link.springer.com/chapter/10.1007/978-3-031-11346-8_4">Link to Paper</a> 
   </li>
<li>Run the output of the first step through deep sort in the link below  
  <a href="https://github.com/nwojke/deep_sort">Deep Sort</a>
  </li>
<li> Segregate poses of different person using jupyter notebook code in mycode folder
</li>
<li>Uplift the poses from 2d to 3d from the below link
  <a href="https://github.com/una-dinosauria/3d-pose-baseline">3D Pose estimation Baseline</a>
 </li>
<li> Place output of the step 4 in unity assets folder and run it to watch the animation </li>
   
</ol>

