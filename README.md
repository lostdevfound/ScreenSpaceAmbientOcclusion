# ScreenSpaceAmbientOcclusion
The OpenCL node to render SSAO inside BM Fusion. The SSAO node needs three inputs: camera space position pass, camera space normal pass and random normals (random normals image can be found inside the example folder).

![demo](https://cloud.githubusercontent.com/assets/14153294/15379361/4c4c6892-1d21-11e6-8e0b-2fc1682b452c.jpg)

Installation:
Copy ssaoFuse file to C:\Program Files\eyeon\Fusion 6.X\Fuses\OpenCL. 
Use the random_normal.tif image as one of the inputs of the ssao node in fusion flow.

How to organize the flow:
![manual](https://cloud.githubusercontent.com/assets/14153294/15379655/45cd24fe-1d24-11e6-9436-b75352981456.jpg)
Note: The node labels on the image are color indexed according to the SSAO input ports
