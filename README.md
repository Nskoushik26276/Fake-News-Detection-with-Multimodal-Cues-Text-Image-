# Fake-News-Detection-with-Multimodal-Cues-Text-Image-
The rise of misinformation and fake news on digital platforms poses a serious challenge to society. This project focuses on detecting fake news by analyzing both textual content and associated images—a multimodal approach that improves prediction accuracy compared to text-only methods.
The system allows users to either:

Enter text and upload an image, or

Provide a news URL, from which the text is automatically extracted.

It uses state-of-the-art deep learning models:

Text Encoding: DistilBERT, a transformer-based language model, extracts meaningful semantic features from news text.

Image Encoding: ResNet-50, a convolutional neural network, extracts visual features from uploaded images.

Multimodal Fusion: The text and image embeddings are combined and passed through a feed-forward classifier that predicts whether the news is Real or Fake.

Key Features:

Supports both manual text input + image upload and automatic news URL processing.

Robust handling of articles with or without images.

Easy-to-use interface for end-users (text input, image upload, URL input).

Probabilistic output showing confidence for Real and Fake classes.

Can be extended for large-scale datasets and further fine-tuning.

Workflow:

User Input: Accepts either text + image or news URL.

Text Processing: Encodes text using DistilBERT.

Image Processing: Encodes uploaded image using ResNet-50.

Feature Fusion: Combines text and image embeddings.

Classification: Predicts Real vs Fake news using a small feed-forward neural network.

Output: Displays class probabilities and predicted label.

Applications:

Social media monitoring and content moderation.

Assisting journalists and fact-checkers in detecting misinformation.

Enhancing trustworthiness of online news platforms.

Link to download the zip file (dataset):-https://drive.google.com/file/d/1r-59MMveBkeE18n1mL7Vz1sqQJaIfN_3/view?usp=sharing
