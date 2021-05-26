# 3D-effects-from-flat-2D-image-with-customisation


2D to 3D Image conversion 


Goal and Vision: 

To visualize and create an image from flat 2D image to 3D image with effects.

Model brief and Implementation:

    • Model approach is to work with input images where we processed images via generating and extracting meshes and analyzing the depth of an image. While extracting depth from the image we will also generate the mesh file (PLY) which can be used in any third party software to visualise (Blender). After generating a mesh file of an image we will do image processing (on multiple parameters) via code by applying different effects at different variable thresholds. 

Research involves around the model:

    • We implemented this model for generating results on any custom images to visualize.
    • Model is available in both the versions like GPU & CPU.
    • We can change the image size dynamically to any resolution where it is working.
    • We can adjust the values of X,Y,Z planner to adjust the movements.
    • We can adjust parameters like -  Background and Context thickness , Extrapolation_thickness.
    • We can also apply depth edge inpainting model repeatedly
	
Implementation towards model:

    • We have set up all the necessary things and models in progression of this model.
    • Put all the images you want to make into 3D , initially this code supports only JPG images however you can modify the image extension in config file for better understanding.
    • Once you have uploaded a file in the correct folder , all you need to run one code file only which generates .npy and .ply file respectively for images in the folder.
    • These generated files help to creative depth in painting by applying effects on the ply and npy file respectively.
    • Once image processing is done , motion based on effects will be generated with the help of moviepy.
    • You can find the final results in defined folders.

Note :
    • This module follows strictly and specific versions for executions.
    • Here , We have used MiDas Dataset for execution.

Code Workflow:
    • Code utilize the necessary packages and libraries to import
    • To execute we follow the below command to run :
        ◦ pip install opencv-python, numpy, matplotlib==2.2.3 ,tensorflow==1.12.0 ,PyQt5 ,h5py, keras, python-dateutil, pytz, pyparsing, six ,imageio.
    • Now just open the MMD and load your character and your generated VMD file and “ENJOY”.

Results:

You can find the resuls once you will run the commands.


Extensions:-

This section has some ideas for extending this article that you may wish to explore.
    • Will extend this module into different motion effects.

If you explore any of these extensions, I’d love to know.

Thank You.
