# IMPORTANCE OF GASTROINTESTINAL DISEASE DETECTION

# APPROACHES FOR COMPUTER-AIDED DIAGNOSIS

# ALGORITHMS

# TOOLS


# KVASIR DATASET - Multi-Class Image-Dataset for Computer-Aided Gastrointestinal Disease Detection
## Dataset Description
Automatic detection of diseases by use of computers is an important, but still unexplored field of research. Such innovations may improve medical practice and refine healthcare systems all over the world. However, datasets containing medical images are hardly available, making reproducibility and comparison of approaches almost impossible. Here, we present Kvasir, a dataset containing images from inside the gastrointestinal (GI) tract. The collection of images is classified into three important anatomical landmarks and three clinically significant findings. In addition, it contains two categories of images related to endoscopic polyp removal. Sorting and annotation of the dataset are performed by medical doctors (experienced endoscopists). In this respect, Kvasir is important for research on both single- and multi-disease computer-aided detection. By providing it, we invite and enable multimedia researchers into the medical domain of detection and retrieval.

## Data Collection By Original Author
The data is collected using endoscopic equipment at Vestre Viken Health Trust (VV) in Norway. The VV consists of 4 hospitals and provides health care to 470.000 people. One of these hospitals (the Bærum Hospital) has a large gastroenterology department from where training data have been collected and will be provided, making the dataset larger in the future. Furthermore, the images are carefully annotated by one or more medical experts from VV and the Cancer Registry of Norway (CRN). The CRN provides new knowledge about cancer through cancer research. It is part of the South-Eastern Norway Regional Health Authority and is organized as an independent institution under the Oslo University Hospital Trust. CRN is responsible for national cancer screening programs to prevent cancer death by discovering cancers or pre-cancerous lesions as early as possible.

## Applications of the Dataset
Our vision is that the available data may eventually help researchers to develop systems that improve the healthcare system in the context of disease detection in videos of the GI tract. Such a system may automate video analysis and endoscopic findings detection in the esophagus, stomach, bowel, and rectum. Important results will include higher detection accuracies, reduced manual labor for medical personnel, reduced average cost, less patient discomfort and possibly increased willingness to undertake the examination. In the end, the improved screening will probably significantly reduce mortality and several luminal GI disease incidents. For direct use in multimedia research areas, the main application area of Kvasir is the automatic detection, classification, and localization of endoscopic pathological findings in an image captured in the GI tract. Thus, the provided dataset can be used in several scenarios where the aim is to develop and evaluate algorithmic analysis of images. Using the same collection of data, researchers can easily compare approaches and experimental results, and results can be reproduced. In particular, in the area of image retrieval and object detection, Kvasir will play an important initial role where the image collection can be divided into training and test sets for developments of and experiments for various image retrieval and object localization methods including search-based systems, neural-networks, video analysis, information retrieval, machine learning, object detection, deep learning, computer vision, data fusion, and big data processing.

## Provenance
The Kvasir dataset was created within the Norwegian FRINATEK project "EONS" (#231687) at Simula Research Laboratory, Norway.

## Data Documentation
The data and the detailed description and usage instructions are published online at the dataset web page http://datasets.simula.no/kvasir/

## Work Flows
The images provided can be used for developing, testing, and comparison of different image recognition and classification approaches regarding their specific procedures.

## Suggested Metrics
Looking at the list of related work in this area, there are a lot of different metrics used, with potentially different names when used in the medical area and the computer science (information retrieval) area. Here, we provide a small list of the most important metrics. For future research, in addition to describing the dataset to a total number of images, total number of images in each class, and the total number of positives, it might be good to provide as many of the metrics below as possible to enable an indirect comparison with older work:

* True positive (TP) The number of correctly identified samples. The number of frames with an endoscopic finding correctly is identified as a frame with an endoscopic finding.
* True negative (TN) The number of correctly identified negative samples, i.e., frames without an endoscopic finding which correctly is identified as a frame without an endoscopic finding.
* False positive (FP) The number of wrongly identified samples, i.e., a commonly called a "false alarm". Frames without an endoscopic finding which is erroneously identified as a frame with an endoscopic finding.
* False negative (FN) The number of wrongly identified negative samples. Frames without an endoscopic finding which erroneously identified as a frame with an endoscopic finding.
* Recall (REC) This metric is also frequently called sensitivity, probability of detection, and true positive rate, and it is the ratio of samples that are correctly identified as positive among all existing positive samples.
* Precision (PREC) This metric is also frequently called the positive predictive value, and shows the ratio of samples that are correctly identified as positive among the returned samples (the fraction of retrieved samples that are relevant).
* Specificity (SPEC) This metric is frequently called the true negative rate, and shows the ratio of negatives that are correctly identified as such (e.g., the fraction of frames without an endoscopic finding are correctly identified as a negative result).
* Accuracy (ACC) The percentage of correctly identified true and false samples.
* Matthews correlation coefficient (MCC) MCC takes into account true and false positives and negatives, and is a balanced measure even if the classes are of very different sizes.
* F1 score (F1) A measure of a test’s accuracy by calculating the harmonic mean of the precision and recall.
In addition to the above metrics, system performance metrics processing speed and resource consumption are of interest. In our work, we have used the achieved frame rate (FPS) as a metric as real-time feedback is important.

## Evaluation:
The dataset was used to generate all results presented in the article KVASIR: A Multi-Class Image Dataset for Computer Aided Gastrointestinal Disease Detection, from the Proceedings of the 8th ACM on Multimedia Systems Conference, 2017.

## Terms of use
The use of the Kvasir dataset is restricted for research and educational purposes only. The use of the Kvasir dataset for other purposes including commercial purposes is forbidden without prior written permission. In all documents and papers that use or refer to the Kvasir dataset or report experimental results based on the Kvasir dataset, a reference to the dataset paper has to be included.

## Contact
Email Michael/paalh (at) simula (dot) no if you have any questions about the dataset and our research activities. We always welcome collaboration and joint research!

## License
Permission to use, copy, modify, and distribute this data and its documentation is hereby granted, provided that both the copyright notice and this permission notice appear in all copies of the data, derivative works or modified versions, and any portions thereof, and that both notices appear in supporting documentation. This THE AUTHORS AND SIMULA RESEARCH LABORATORY DISCLAIM ANY LIABILITY OF ANY KIND FOR ANY DAMAGES WHATSOEVER RESULTING FROM THE USE OF THIS DATA.

# Links
Dataset: https://www.kaggle.com/datasets/abdallahwagih/kvasir-dataset-for-classification-and-segmentation/data
