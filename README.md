# Number of Skyrmion on the frame. Number of Skyrmion entered/ left the geometry


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/zkhodzhaev/skyrmion/blob/main/circle_object_count.ipynb)



Data analysis of the Skyrmions aka circular objects inside a predefined geometry.

Visualization best showcases the underlying problem that we will solve in this script,so this is the problem:

<img src="https://user-images.githubusercontent.com/21960382/126055787-7572ea29-d3fa-4095-aaa4-6491b4b1bed0.gif" width="500" height="250"/>

Let's visualize and see what array visualizes. We have [x,y,1,3] 3 data= mx, my, mz. Let's decide what to take:
![image](https://user-images.githubusercontent.com/21960382/126055809-762635d4-19d2-470b-81af-eac821f15396.png)

Mz seems a plausable. Now, let's define boundary where will consider the Skyrmion inside or outside of the Geometry. I will define 2 lines for boundaries.These 2 boundaries will be used for entering and leaving the geometry. The message will appear at the top of each plot to give more detailes:

<img src="https://user-images.githubusercontent.com/21960382/126056090-bf2a3e9b-046b-4681-8c6b-7556902051ef.png" width="380" height="400"/>

More detailed script is in jupyter notebook, and also you can try a sample code with a colab, following the link. If you want to try yourself, there are files named "input" that can feed into teh script:

[Main script (jupyter notebook): circle_object_count.ipynb](https://github.com/zkhodzhaev/skyrmion/blob/886340b5997b9f5eb57213c183bc3de0808fe536/circle_object_count.ipynb)
