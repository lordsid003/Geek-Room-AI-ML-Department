## Advancing to Month 2 Projects 🤟

Time to level-up our knowledge to understand standard Machine Learning Techniques namely: 
  <ul>
    <li>
      <i><b>Linear Regression (from scratch)</b></i>
    </li>
     <li>
      <i><b>Binary Classification</b></i>
    </li>
     <li>
      <i><b>Multi-Class Classification</b></i>
    </li>
  </ul>
These techniques are part of Supervised Learning and lay the foundation for further complex tasks of decision-making using Artificial Intelligence. 

## TASK📎:
** <i>All projects to be covered </i><br>
Create a folder by your team name. Each member of the team must contribute in the project. To ensure this, add a <b><i>README.md</i></b> containing: 
<ul>
  <li>
    <i>Team Details</i>
  </li>
  <li>
    <i>Summary about what you learnt (30-50 words)</i>
  </li>
  <li>
    <i>Contribution made by each member</i>
  </li>
</ul>
<b>Example</b>: 
<ul>
  <li>
    Team Details:
      <ol>
        <li><b><i>Siddharth Verma</i></b>: Trained model using opencv/ mediapipe</li>
        <li><b><i>Arnav Kohli</i></b>: Fine tuned hyper-parameters to increase efficiency</li>
        <li><b><i>Pratham Batra</i></b>: Loaded and deployed the model for external devices/ IP addresses</li>
      </ol>
  </li>
  <li>
    Researched and learnt about Computer Vision applications with industry standards. Used opencv and mediapipe libraries to train a model for posture detection of a person using webcams/ external cameras and IP cameras. Used body landmarks provided by mediapipe and calculated required angles using numpy for analyzing postures.
  </li>
</ul>

## PROJECTS 📚: 
<ol>
  <li>
    <b>Taxi-Fare prediction:</b> Linear Regression to predict fare in a Taxi ride based on several trip factors. Use standard python libraries (Pandas, 
    matplotlib, seaborn, numpy) for loading and  understanding datasets, Feature Engineering and extraction, Data visualization and model training from 
    scratch. The point is to understand the key concepts behind mathematical analysis of Linear Regression. You can refer to resources shared to you (pdf 
    document shared earlier). <br><br>
    <b>Tips: </b> <br>
    <ul>
      <li><i>Compute cost using mean-squared or RMS error (loss function).</i></li>
      <li><i>Compute gradient (partial derivative of cost function with parameters) to calculate the slope (rate of change) of each parameter which affects 
        the curve-fiting with a learning rate.</i></li>
      <li><i>Use gradient-descent to train the model by updating parameters and fitting the predictions to target labels over several iterations.</i></li>
    </ul>
    
  <b>Dataset link:</b> [Uber Fares Dataset (kaggle.com)](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset/data)

  <span>
    <img src="https://i.ytimg.com/vi/2cK_l1hbQao/maxresdefault.jpg?raw=true" width="400">&ensp;
    <img src="https://raw.githubusercontent.com/Masterx-AI/Project_Uber_Fare_Prediction/main/Uber1.jpg?raw=true" width="340">
  </span>
  
  </li>
  <br>
  
  <li>
    <b>Customer-Churn Rate prediction:</b> Using Binary classification (2 target labels, Example: Yes/No) to determine the customer-churn rate on a 
    product. <i><b>“Churn Rate refers to the percentage of customers quiting your services/products per month.”</b>.</i><br>
    You can use Scikit-Learn/ Pytorch/ TensorFlow to train and evaluate a Binary Classification model to predict whether a customer quits or continues the 
    usage of the product based on several features in given Dataset. Use standard python libraries to preform loading, analyzing, visualizing and 
    extracting features from Dataset. <br><br>
    <b>Tips: </b> <br>
    <ul>
      <li><i>Analyzing relevant features affecting customer retenƟon (These are not significant to predict churn rate) </i></li>
      <li><i>Analyzing reviews and client feedbacks</i></li>
      <li><i>Extracting features and Engineering new features</i></li>
      <li><i>Sigmoid or tanh activation for probability calculation</i></li>
    </ul>
    
  <b>Dataset link:</b> [Telco Customer Churn (kaggle.com)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

  <span>
    <img src="https://miro.medium.com/max/1280/1*iKo3KI4kqkZ47W7pmmH4cw.png?raw=true" width="380">&ensp;
    <img src= "https://th.bing.com/th/id/R.d84994f3e92d43d8af39ae22eeb0984e?rik=lEOln%2fFlLiGFrg&riu=http%3a%2f%2fdatabeauty.com%2ffigures%2f2018-01-16-From-Perceptron-to-Deep-Learning%2ftanh.png&ehk=RJb27e9s0uPUU%2fZGPahUYLWKrhgonraF3KlRdtjU7vw%3d&risl=&pid=ImgRaw&r=0?raw=true" width="270">
  </span>
  
  </li>
  <br>
  
  <li>
    <b>MNIST Digit Classification:</b> Inculcate the power of image analysis of ML to train a Multi-Class Classification model which determines the Hand-
    written digits using Artificial Neural Networks (ANNs) using Tensorflow/ PyTorch. <br>
    Use Keras to load the famous “MNIST” dataset containing thousands of hand-written digit images with their correct target labels. <br><br>
    <b>Workflow:</b> <br>
    <ul>
      <li><i>Loading and analyzing dataset using Scikit-Learn and matplotlib</i></li>
      <li><i>Image pixelation and Data normalization as a part of processing</i></li>
      <li><i>Splitting dataset into Testing and Training data</i></li>
      <li><i>Creating ANN with several layers and neurons</i></li>
      <li><i>Evaluating model and making predictions</i></li>
      <li><i>Saving the model for future fine tuning or loading</i></li>
      <li><i>Deploying model on streamlit / Huggingface </i></li>
      <li><i>Further integration with personalized backend for model loading with UI </i></li>
    </ul>
  <br>
  <b>Dataset:</b> MNIST Dataset is already available in keras Dataset module. To load this dataset: <br><br>

  ```
  !pip install keras 
  ```
  ```
  from keras.datasets import mnist
  ```
  ```
  (x_train, y_train), (x_test, y_test) = mnist.load_data() 
  ```

  <span>
    <img src="https://miro.medium.com/max/1058/1*-GB7wyRyuFfpSZ_4y4DnNA.png?raw=true" width="500">&ensp;
    <img src= "https://machinelearningmastery.com/wp-content/uploads/2019/02/Plot-of-a-Subset-of-Images-from-the-MNIST-Dataset.png?raw=true" width="365">
  </span>
  
  </li>
    
