<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1 align="center">Audio Classification System</h1>

<p>This project focuses on developing an Audio Classification system to categorize audio signals into predefined classes such as speech, music, and noise using advanced signal processing techniques and neural networks.</p>

<h2>Features</h2>
<ul>
    <li>Classification of audio signals into speech, music, and noise</li>
    <li>Signal processing techniques for feature extraction</li>
    <li>Calculation of key audio features: MFCCs, Zero-Crossing Rate (ZCR), and Root Mean Square Energy (RMSE)</li>
    <li>Integration of pitch detection algorithms</li>
    <li>Neural network-based classification for improved accuracy</li>
</ul>

<h2>Technical Overview</h2>
<ul>
    <li><b>Feature Extraction:</b> Extracted key features such as:
        <ul>
            <li><b>MFCCs:</b> Mel-Frequency Cepstral Coefficients to capture spectral properties of audio signals.</li>
            <li><b>ZCR:</b> Zero-Crossing Rate to analyze signal changes in the time domain.</li>
            <li><b>RMSE:</b> Root Mean Square Energy to measure signal power over time.</li>
        </ul>
    </li>
    <li><b>Pitch Detection:</b> Implemented algorithms to identify pitch, aiding in distinguishing between audio classes.</li>
    <li><b>Classification:</b> Utilized a neural network model for accurate categorization of audio signals.</li>
</ul>

<h2>Dataset</h2>
<p>The project uses the <a href="https://www.kaggle.com/code/prabhavsingh/urbansound8k-classification/input" target="_blank">UrbanSound8K dataset</a> for training and testing purposes. This dataset contains a wide variety of labeled audio samples, making it ideal for building and evaluating the classification system.</p>

<h2>Usage</h2>
<p>This Audio Classification system is designed for applications requiring audio signal categorization, such as speech recognition, music categorization, and environmental noise detection. The implementation provides a reliable and efficient approach to classify audio signals.</p>

<h2>Acknowledgments</h2>
<ul>
    <li>UrbanSound8K dataset from Kaggle</li>
    <li>References on audio signal processing and classification</li>
    <li>Open source neural network frameworks</li>
    <li>Support and guidance from the Signals and Systems Lab course at NUST College of Electrical and Mechanical Engineering</li>
</ul>

</body>
</html>
