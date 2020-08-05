# Single View Metrology: Step By Step
An implementation of Single View Metrology (Criminisi99) with step-by-step guidance in a Jupyter Notebook.

This shows how we can obtain 3D information from a single perspective image without knowing the camera parameters in advance. 
By manually identifying parallel lines and planes in the image, we can reconstruct the projection matrix up to a scale. The scales parameters can be further solved given reference (known or imagined) lengths. Then we can reconstruct a 3D model using careful measurement in the image space and homography-based texture mapping.
