# Bachelorthesis
## Image-based segmentation and localization of surgical instruments using deep neural networks
Here you can find my [bachelorthesis]{https://github.com/Amyy/bachelor_thesis/blob/main/thesis.pdf} and the corresponding LaTeX sourcecode.

### Abstract
Segmentation and localization of surgical instruments in endoscopic videos during minimally
invasive surgery is a fundamental requirement for supporting the surgeon during this
sophisticated surgical technique. Here, a CNN-based deep learning method is used to get
the positional information of the instrument directly out of the video frames without further
modifications. In this work, the segmentation network TernausNet-11 is extended to a
network that also solves the localization task. The instrument segmentation is addressed
as a binary problem, where every pixel of the input image is labeled as instrument or
background. The instrument location is obtained by the prediction of heatmaps where the
center point of the instrument is located. That makes it possible for the network to use
the information learned for the segmentation task to improve the localization results, as
the weights of the network are shared for both tasks. All proposed methods are evaluated
on the robotic dataset of MICCAI 2015 Endoscopic Vision subchallenge according to the
challenge guidelines. The results of the experiments show that the proposed method is
able to solve the segmentation task on the same level as state-of-the-art results. For the
localization task, the models tested particularly on the test datasets achieve lower results
than current state-of-the-art methods. The models trained in leave-one-surgery-out fashion
outperform current state-of-the-art methods.

