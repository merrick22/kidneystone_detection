# kidneystone_detection

KIDNEY STONE disease occurs due to the accumulation
of salt and mineral crystals excreted in the urine and
turning into stones. 

A type of Convolutional Neural Network (CNN) named Inception-v3 is
generally used to aid image analysis and object detection.

There are many studies on the diagnosis and classification
of kidney diseases by machine learning methods. In this study,
a synthetic kidney function test (KFT) data set including age,
gender, urea, creatinine, and glomerular filtration rate was
created for the analysis of kidney disease.

![image](https://user-images.githubusercontent.com/117385630/236230528-65e93789-bcc6-46bd-8bde-3d817128054f.png)

 In the first step,
different-sized x-ray images are converted into 64x80 fixedsize images. Then resized images are subjected to grayscale
conversion processes in the second step. In the third step, the
gray level values obtained from the image are extracted in the
CSV file. These values consist of 5120 columns are labeled as
patient or healthy according to the presence of kidney stones,
catheters, or both found from the x-ray images. Images
without any kidney stones or catheters are labeled as healthy,
while images with stones or catheters are labeled as patients.
This labeling process has been done by taking into account the
opinions of the specialist doctors working in the Urology
department. In the obtained dataset, 182 images have a patient
label, while 39 images have a healthy label.

![image](https://user-images.githubusercontent.com/117385630/236230821-730a8118-e09d-4ec9-b636-74d0007f3379.png)



