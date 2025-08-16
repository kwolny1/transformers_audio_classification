# Transformers - Audio Classification
Comparison between Wav2Vec2.0, LSTM-CNN Network and Audio Spectrogram Transformer models. 

The primary objective of this project was to compare the performance of several deep learning architectures on the audio classification task using the Speech Commands dataset. Beyond simple benchmarking, we focused on understanding how key training components (hyperparameters and data augmentations) impact overall model performance in practice. We used these three models:

 - LSTM-CNN network,
- Wav2Vec2.0,
- Audio Spectrogram Transformer (AST).
- 
AST and Wav2Vec2.0 models were initialized with pretrained weights and fine-tuned with frozen feature extractors. The LSTM-CNN network was trained from scratch without any pretraining. All experiments were conducted using the TensorFlow framework and selected Hugging Face libraries within the Google Colab environment.

Results are descripted in details in **DeepLearning_Project_2___Transformers___Rzepinski__Wolny.pdf**. 
