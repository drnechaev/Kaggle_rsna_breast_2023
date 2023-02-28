RSNA Screening Mammography Breast Cancer Detection
112  in competention (pF1 0.43, top7%)

<h1>rsna-1imp-tpu-train</h1>
Prepare data set from dicom to jpg, croping image, resize to 768, 1344 and write into tfrecords fileformat

<h1>rsna-1imp-tpu-train</h1>
train model on tpu

Model:

2 inputs:
    1: prepared image
    2: age and implant flag

Model:
<img src='https://github.com/drnechaev/Kaggle_rsna_breast_2023/blob/main/Model.png' alt='model'/>
                                                     
<h1>rsna-1imp-tpu-train</h1>
Loading trainded model and test
