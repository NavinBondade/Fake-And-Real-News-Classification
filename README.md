# Fake And Real News Classification
<img src="https://ichef.bbci.co.uk/news/976/cpsprodpb/089D/production/_111750220_gettyimages-1215064495.jpg" alt="Fake_And_Real_News_Classification" width="1000" height="510">
<p>Fake news is one of the most painful headaches in today's world. They lead to the spread of fake and misleading information that has many times results in violent protests or damage to the reputation of an organization or person. To tackle this problem I have created a deep learning system that is capable of identifying fake news in a couple of seconds with an <b>accuracy of 99%.</b></p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Numpy</li>
  <li>Sklearn</li>
  <li>Spacy</li>
  <li>BeautifulSoup</li>
  <li>Contractions</li>
  <li>Regular Expression</li>
</ul>
<h2>Word Cloud Representation</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Word%20Cloud%20Representation.jpg" alt="wordcloud" >
<h2>Model Details</h2>
<p>For the conversion of text data to numeric, I have used Keras word to sequence function. The deep learning model at its core uses single one-dimensional convolution neural network layers followed by Max pooling and dropout layer,  it also uses three dense layers for decision making. All the layers use RELU as an activation function except the last dense layer that uses the sigmoid activation function.</p>
<br>
<p align="center">
  <img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/model.png" height="700">
</p>
<h2>Model Traning</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Model%20Training.jpg" alt="loss_accuracy">
<p>The model was trained for 2 epochs. During training, the model uses Adam as an optimizer for performing backpropagation and uses binary_crossentropy as the loss function to penalize model more when it makes false predection.</p>
<h2>Model Evaluation on Development Dataset</h2>
<h3>Accuracy and Loss</h3>
<ul>
  <li><b>Training Data Accuracy: 99%</b></li>
  <li><b>Test Data Accuracy: 99%</b></li>
  <li><b>Training Data Loss: 0.0201</b></li> 
  <li><b>Test Data Loss: 0.006</b></li> 
</ul>
<h2>Confusion Matrix on Development Dataset</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Confusion%20Matrix%20Development%20Data.png">
<h2>Receiver Operating Characteristics (ROC) on Development Dataset</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/ROC.png">  
<h2>Precision vs. Recall curve on Development Dataset</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Precision%20vs.%20Recall%20curve.png">

<h2>Classification Report on Development Dataset</h2>
<img src="https://github.com/NavinBondade/Fake_And_Real_News_Classification/blob/main/Graphs/Classification%20Report%20development%20data.png">
    
  







