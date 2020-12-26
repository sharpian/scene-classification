# Scene Classification for Sports Video Summarization Using Transfer Learning
This paper proposes a novel method for sports video scene classification with the particular intention of video summarization. Creating and publishing a shorter version of the video is more interesting than a full version due to instant entertainment. Generating shorter summaries of the videos is a tedious task that requires significant labor hours and unnecessary machine occupation. Due to the growing demand for video summarization in marketing, advertising agencies, awareness videos, documentaries, and other interest groups, researchers are continuously proposing automation frameworks and novel schemes. Since the scene classification is a fundamental component of video summarization and video analysis, the quality of scene classification is particularly important. This article focuses on various practical implementation gaps over the existing techniques and presents a method to achieve high-quality of scene classification. We consider cricket as a case study and classify five scene categories, i.e., batting, bowling, boundary, crowd and close-up. We employ our model using pre-trained AlexNet Convolutional Neural Network (CNN) for scene classification. The proposed method employs new, fully connected layers in an encoder fashion. We employ data augmentation to achieve a high accuracy of 99.26% over a smaller dataset. We conduct a performance comparison against baseline approaches to prove the superiority of the method as well as state-of-the-art models. We evaluate our performance results on cricket videos and compare various deep-learning models, i.e., Inception V3, Visual Geometry Group (VGGNet16, VGGNet19), Residual Network (ResNet50), and AlexNet. Our experiments demonstrate that our method with AlexNet CNN produces better results than existing proposals.
![System Model](https://www.mdpi.com/sensors/sensors-20-01702/article_deploy/html/images/sensors-20-01702-ag.png)
# Program code
python, keras
# Dataset
cricket videos dataset from youtube.
For performance evaluations, we have selected various sports videos from YouTube™, considering different series and different lighting conditions. Our dataset consists of the following videos. Cricket 2014 New Zealand v South Africa 1st ODI Highlights - YouTube [29], World Record 438 Match-South Africa vs. Australia- Part 2 - YouTube [30], Pakistan vs. Australia 3rd ODI Full Highlights - YouTube [31], 1st ODI: Pakistan vs. Australia HD Full Highlights - YouTube [32].

# Results

#Citation
Rafiq, M.; Rafiq, G.; Agyeman, R.; Choi, G.S.; Jin, S.-I. Scene Classification for Sports Video Summarization Using Transfer Learning. Sensors 2020, 20, 1702.
Sensors 2020, 20(6), 1702; https://doi.org/10.3390/s20061702

