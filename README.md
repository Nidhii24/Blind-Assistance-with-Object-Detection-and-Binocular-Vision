# Blind-Assistance-with-Object-Detection-and-Binocular-Vision

While discussing the challenges that the world's population faces, we frequently overlook those who are the most affected by the current situation: the blind and visually impaired. According to the World Health Organization, there are about 2.2 billion people worldwide who have some sort of vision impairment. Blind people are not automatically entitled to basic care needs in most nations since they are not defined as clinically extremely vulnerable.<br />
With breakthroughs in Artificial Intelligence and Technology, we are better positioned to improve this group's quality of life. This technology, also known as assistive or adaptive technology, is constantly growing and has helped people with vision loss overcome many barriers to access.
We were inspired to embark on a vision assistance project to assist the blind, and we came across a problem statement to develop this system using Binocular Vision, Image Processing, and Object Detection. The goal is to create a blind aid equipment that includes two cameras mounted on a walking stick that is commonly used by blind people. Binocular vision was proposed as an alternative to monocular vision. One camera alone cannot accurately imitate the human vision system, but two cameras can be used to sense depth and interactions between objects. Each camera captures slightly different spatial information and sends it to the model. The model then uses the differences between the two cameras to calculate the parallax of the pictures and evaluate distance and depth.<br />
Following the acquisition of the binocular image, we run it through a CNN-based object detection model to help us identify the classes to which they belong and therefore lead the visually impaired along their journey. A pressure application device linked to the person's body serves as a means of communication between the model and the visually handicapped. Obstacles in everyday life can be related to various pressures, which tell the individual how far or close the object is. With the dependence on technology, we may help these individuals find independence for themselves.
<br />
<br />
'''
Run pip install -r requirements.txt to install all the necessary packages.
'''
<br />
<br />
'''
To run the main file and estimate depth of the detected object:<br />
python stereoVision.py
'''