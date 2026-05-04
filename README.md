Deep learning methods have shown early progress
in analyzing complicated electrocardiogram signals, particularly
in tasks like heartbeat classification and arrhythmia detection.
Analyzing health-related data has always been a complex
challenge. In this study, a novel method for arrhythmia
classification that combines a hybrid unidirectional and
bidirectional Recurrent Neural Network (RNN) with multilayered
dilated convolutional neural network (CNN) is implemented. The
model is trained and validated on the MIT-BIH arrhythmia
dataset, showing significant improvements in both performance
and interpretability by integrating features with the dilated
CNN framework. For the reduction of noise present in the
dataset, Discrete Wavelet Transform (DWT) is applied using
the symlet function. To counteract the class imbalance issue,
Generative Adversarial Network (GAN) is utilized in conjunction
with a Markov Chain to synthesize new data, recreating
underrepresented signal patterns. The hybrid architecture
proposed here capitalizes on the strengths of both multilayered
dilated CNNs and different types of RNN units, specifically,
bidirectional units such as BiGRU (Bidirectional Gated Recurrent
Units) and BiLSTM (Bidirectional Long Short-Term Memory), as
well as unidirectional units like GRU and LSTM. These layers
work together to extract and combine desirable features. The
experimental results indicate that the model achieves impressive
metrics, including an overall accuracy of 98.35%. A key outcome
of this research is the significant reduction in computation time
and effective mitigation of class imbalance through integrating
diverse and realistic synthetic data to enhance the training
process.
