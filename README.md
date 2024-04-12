# CNN_VGG_BrainTumorClassification
This was a practice deep learning project. This project involves Convolutional Neural Networks and Image Classification for Brain Tumor MRI Data. The architecture I'm implementing is a modified VGG Conv Net in TensorFlow. The source code is called CNN_PET.py (I initially intended to use PET (positron emission tomography) images). Email Jgraham0@msn.com for full training/val dataset, it's too big to upload here. Dropout regularization was implemented to reduce overfitting of the model. Algorithm runs with classification accuracy 98%, validation accuracy 96%. In future, would be good to collate multiple different sources of data, so that algorithm is fully generalizable to arbitrary MRI data. 

Part of the rationale for approaching this standard DL problem is that I'm a research assistant for Dr. Lena Palaniyappan's lab (UWO/McGill). I'd like to use transfer learning to generalize this model in order to approach a slightly different problem: classification of psychosis via MRI data. Analyzing the activation outputs layer by layer may yield potential insight into novel schizophrenia biomarkers in the brain, as well as potentially providing quantitative in-vivo clinical diagnostic criteria for schizophrenia and other psychosis-based disorders.

<img src="https://i.ibb.co/gSwXr1v/Screen-Shot-2022-03-29-at-9-01-54-PM.png" style="height:100px,width:100px"></img>

<img src="https://i.ibb.co/HPw2Qgn/Screen-Shot-2022-03-29-at-9-01-47-PM.png" style="height:100px,width:100px"></img>

