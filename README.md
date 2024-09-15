## About The Project: 

Air pollution is a major global health issue, identified by the World Health Organization (WHO) as one of the top threats to human well-being. 
In 2019, air pollution caused approximately 4.2 million deaths, with fine particulate matter (PM2.5) being a significant contributor. 
Recently, advancements in computer vision and deep learning have led to the use of convolutional neural networks (CNNs) for estimating PM2.5 levels from images.
However, many of these methods treat PM2.5 estimation as a classification task, which limits their effectiveness to specific regions or times.

We propose a novel CNN model with dense connections and diverse convolutional kernels to estimate PM2.5 concentrations from images more accurately. 
This model, named the Throughout the Day PM2.5 Convolutional Neural Network (TDPM-CNN), is designed to work with both daytime and nighttime images. 
It combines the original image with high-frequency features that capture detailed structures like building edges and low-frequency features that represent overall color patterns. 
This approach aims to improve the accuracy and generalizability of PM2.5 concentration predictions.

## Comparison with SOTA  PM2.5 estimation methods


<p align="center">
<img src="https://github.com/nrmkarthi/Airquality_Prediction/blob/main/1.png" alt="System Architecture" width="600" height="500">
</p>

<p align="center">
<img src="https://github.com/nrmkarthi/Airquality_Prediction/blob/main/2.png" alt="System Architecture" width="700" height="1000">
</p>

<p align="center">
<img src="https://github.com/nrmkarthi/Airquality_Prediction/blob/main/3.png" alt="System Architecture" width="700" height="1000">
</p>

<p align="center">
<img src="https://github.com/nrmkarthi/Airquality_Prediction/blob/main/4.png" alt="System Architecture" width="700" height="1000">
</p>


## Approach:
1.Global Health Threat: Air pollution is identified by the WHO as a significant threat to human health. <br>
2.Impact in 2019: In 2019, air pollution caused approximately 4.2 million deaths, with PM2.5 as a major pollutant. <br>
3.Technological Advances: Recent advancements in computer vision and deep learning have led to innovative methods for estimating PM2.5 levels. <br>
4.Use of CNNs: Convolutional neural networks (CNNs) have become popular for estimating PM2.5 concentrations from images. <br>
5.Limitations of Current Methods: Many existing methods treat PM2.5 estimation as a classification problem, limiting their applicability. <br>
6.Proposed Model: We propose a new CNN model with dense connections and multi-kernel convolutional layers. <br>
7.Name: The model is called Throughout the Day PM2.5 Convolutional Neural Network (TDPM-CNN). <br>
8.Day and Night: The model can use both daytime and nighttime images for prediction. <br>
9.Feature Combination: It processes a combination of the original image, high-frequency features (e.g., building edges), and low-frequency features (e.g., color distribution).<br>
10.Improved Accuracy: This approach aims to enhance the accuracy and generalizability of PM2.5 concentration predictions.

## Datasets:
1. Rouniyar, A., Utomo, S., A, J. & Hsiung, P.-A. Air pollution image dataset from india and nepal (2023). URL https://www.kaggle.com/ds/3152196.<br>
2.https://www.windy.com (2023). <br>
3.https://rtsp.me/embed/K9BbYSyf/ (2023).


## References:
1.Utomo SRouniyar AHsu HHsiung P(2023)Federated Adversarial Training Strategies for Achieving Privacy and Security in Sustainable Smart City Applications Future Internet 
10.3390/fi1511037115:11(371)Online publication date: 20-Nov-2023 <br>
2.J. Wang, L. Jin, X. Li, S. He, M. Huang and H. Wang, "A Hybrid Air Quality Index Prediction Model Based on CNN and Attention Gate Unit," in 
IEEE Access, vol. 10, pp. 113343-113354, 2022, doi: 10.1109/ACCESS.2022.3217242. <br>
3.https://www.who.int/data/gho/data/indicators/indicator-details/GHO/concentrations-of-fine-particulate-matter-(pm2-5) <br>
4.Z. Wang et al., "Air Quality Measurement Based on Double-Channel Convolutional Neural Network Ensemble Learning," 
in IEEE Access, vol. 7, pp. 145067-145081, 2019, doi: 10.1109/ACCESS.2019.2945805.



