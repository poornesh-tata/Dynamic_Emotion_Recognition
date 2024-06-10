# Dynamic Emotion Recognition 

# Abstract
Emotion recognition is an advanced technology used to interpret and classify human emotions based on facial expressions and non-verbal cues. 
According to the history involved, spoken communication reflects 7% of the message in personal communication. Voice gives 38% and facial expression produces 55% of the message. As per research, the prominent descriptors of feelings of humans are “Emotions’’.
It is essential for simple and straightforward recognition of human psychology at particular instant without really asking them.
Users need human-like interactions to better communicate with computers i.e., Human Computer Interaction (HCI) which is essential for the humanization of AI.
This model can be used in various real time applications such as human computer interactions i.e., for virtual assistants, For personalised learning, to improve customer service, healthcare monitoring, security and surveillance etc.,

# OpenCV 
A python library of programming functions mainly for real-time computer vision. It contains a main module called a cv2. 
Webcam was accessed using the cv2 module of python and frames are accessed continuously.
# Haar-Cascade 
Haar cascade is an algorithm that can detect objects in images, irrespective of their scale in image. It is computationally less expensive, a fast algorithm, and gives high accuracy.
# Convolutional Neural Networks (CNN)
A Convolutional Neural Network, also known as CNN or ConvNet, is a class of neural networks that specializes in processing data that has a grid-like topology, such as an image. Here we have used CNN's to extract spatial features from frames obtained by input feed of our webcam.
# Long-Short-Term-Memory (LSTM)
The LSTM network, acknowledged for its adeptness in capturing temporal relationships, receives these sequential spatial features and engages in temporal modeling.

# Conclusion
This project explored the development of a hybrid CNN-LSTM model for video-based emotion recognition. We addressed the limitations of CNNs in capturing the temporal dynamics of emotions within video sequences. The proposed model leverages the strengths of both architectures:
<br>
•  CNNs: Effectively extract informative spatial features (facial landmarks, wrinkles) from each video frame.
<br>
•  LSTMs: Analyze the sequence of feature vectors, capturing the evolution of expressions over time.
<br>
This combined approach leads to a more comprehensive understanding of the emotional content in videos. Our findings demonstrate that the hybrid CNN-LSTM model achieves significantly higher accuracy in recognizing emotions compared to using CNNs alone.
Furthermore, we discussed the challenges associated with real-world webcam-based emotion recognition, including factors like lighting variations, user characteristics, and webcam limitations.

# Future Scope
This project lays a strong foundation for future advancements in video-based emotion recognition using hybrid CNN-LSTM models. Here are some exciting possibilities to explore:
<br>
•  Multi-modal Integration: Extend the model beyond visual cues by incorporating additional modalities like voice analysis and body language recognition. This can provide a richer understanding of emotions and lead to even more accurate predictions.
<br>
•  Personalization and Adaptation: Develop mechanisms for the model to adapt to individual users over time. This could involve learning personalized expression patterns and improving accuracy for specific individuals.
<br>
•  Real-time Processing: Optimize the model for real-time processing, enabling applications like real-time sentiment analysis during video conferencing or emotional response measurement in educational settings.

