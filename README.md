# SkyCam

[paper] [project-page] ![Video](https://user-images.githubusercontent.com/8151641/114007395-97258400-9861-11eb-9b28-9be0328c1d18.mp4)

![skycamgif](https://user-images.githubusercontent.com/8151641/114010516-7579cc00-9864-11eb-9bf6-5b155b9e7c47.gif)


SkyCam dataset is a collection of sky images from a variety of locations with diverse topological characteristics (Swiss Jura, Plateau and Pre-Alps regions), from both single and stereo camera settings coupled with a high-accuracy pyranometers. The dataset was collected with a high frequency with a data sample every 10 seconds. 13 images with different exposures times are generated along with a post-processed HDR images and a solar radiance values for each of the cameras and locations. We hope that SkyCam dataset will enable researchers to tackle the problem of short-term local camera-based solar radiance prediction. 

### Dataset Description 

Switzerland is a perfect testing ground for creating a dataset that aims to tackle the problem of short-term solar radiation prediction due to its diverse topological features and volatile meteorological conditions\cite{brunner}. To this extend image and solar radiance capturing equipment was set to three topologically distinct locations, acquiring observations over the span of a year.

![image](https://user-images.githubusercontent.com/8151641/114012832-208b8500-9867-11eb-9574-0e227c3f2751.png)

In Bern a stereo camera setting was deployed while in Neuchâtel and Alpnach a single camera was used. In all sites a high-accuracy pyranometer was used in order to acquire the irradiance values with high precision. All camera are industrial-grade CMOS cameras with an appropriate protective casing. The pyranometer is a Hukseflux SR30 designed for for Photovoltaic system performance monitorin and meteorological networks. The solar radiation is received by a plane surface and measured in W/m^2, from a 180° field of view angle
![image](https://user-images.githubusercontent.com/8151641/114012908-3436eb80-9867-11eb-835e-af1166289e7e.png)

The SkyCam dataset is a collection of images from 365 days from three different locations and four cameras. Each day has on average 12 hours between dawn and dusk and images are captures with a frequency of 10 seconds. That means that we have approximately 1576800 timestamps per camera. The total size of the dataset is approximately 16 TeraBytes. For each time stamp each camera acquires a series of 13 photographs with different exposure times. After the collection the images are post-processed in order to generate a High-Dynamic-Range (HDR) image. At the same time the solar radiance value is measured by the pyranometer. In Figure 3 we can observe how a particular timestamp looks like. The original resolution of each captured image is 1200x1200 pixels while the generated HDR image has a resolution of 600x600 pixels.

![image](https://user-images.githubusercontent.com/8151641/114012935-4153da80-9867-11eb-9e67-9097eacad5e9.png)

### Access Instructions

To request access to the dataset please send a enquiry to evangelos.ntavelis [at] csem [dot] ch

Option 1: Upon request will give you the credentials to access our ftp server

Option 2: Due to the size of the dataset, copying the files to a physical drive will be a faster solution.

### Citation

If you find the SkyCam dataset useful to your research/work please cite:

### Licence


### Acknowledgements
The  development  of  the  SkyCam dataset  was funded by the  Swiss  Federal  Office of  Energy  under  grant  SI/50151 as a collaborative project between CSEM and Meteotest.

![csem logo](https://user-images.githubusercontent.com/8151641/114016192-e1f7c980-986a-11eb-871c-4e0abaa2a16b.png)
![meteotest](https://user-images.githubusercontent.com/8151641/114016207-e3c18d00-986a-11eb-8b89-d92f87737cd5.png)

