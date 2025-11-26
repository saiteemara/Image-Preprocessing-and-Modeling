<h1>🖼️ Image Classification Using KNN & Random Forest</h1>

<h2>🔍 Overview</h2>
<p>
This project performs <strong>image classification</strong> using traditional Machine Learning models 
(KNN and RandomForest). Images are flattened into numerical vectors, scaled using StandardScaler, 
and evaluated for accuracy. The project also includes <strong>Individual Image Testing</strong> to verify real-world predictions.
</p>

<hr>

<h2>🎯 Project Objectives</h2>
<ul>
  <li>Load and preprocess an image dataset</li>
  <li>Convert images into numerical feature vectors</li>
  <li>Scale data using StandardScaler</li>
  <li>Train and evaluate ML models (KNN & RandomForest)</li>
  <li>Test predictions on <strong>individual input images</strong></li>
</ul>

<hr>

<h2>📂 Workflow</h2>
<ol>
  <li><strong>Load Dataset</strong> and create DataFrame</li>
  <li><strong>Split</strong> into training and testing sets</li>
  <li><strong>Scale Training Data</strong> using StandardScaler</li>
  <li>Train Models:
    <ul>
      <li><strong>K-Nearest Neighbors (KNN)</strong></li>
      <li><strong>RandomForest Classifier</strong></li>
    </ul>
  </li>
  <li><strong>Evaluate accuracy</strong> on test data</li>
  <li><strong>Sample Testing</strong> on test dataset</li>
  <li><strong>Individual Image Testing</strong> with external images</li>
</ol>

<hr>

<h2>🧪 Models Used</h2>
<ul>
  <li><strong>RandomForest Classifier</strong></li>
  <li><strong>K-Nearest Neighbors (KNN)</strong></li>
</ul>

<hr>

<h2>📊 Model Performance</h2>
<ul>
  <li><strong>RandomForest Accuracy:</strong> 0.7748</li>
  <li><strong>KNN Accuracy:</strong> 0.5278</li>
</ul>

<p>
✅ RandomForest showed better performance due to higher stability in high-dimensional image data.
</p>

<hr>

<h2>🧪 Individual Image Testing</h2>
<p>
The model was tested on <strong>single external images</strong> not included in the training dataset.
Images were:
</p>
<ul>
  <li>Loaded using OpenCV/PIL</li>
  <li>Resized to match training dimensions</li>
  <li>Flattened into feature vectors</li>
  <li>Scaled using the same StandardScaler</li>
  <li>Passed to the trained model for prediction</li>
</ul>

<p>
✅ Example output:<br>
<strong>Input:</strong> Uploaded image<br>
<strong>Prediction:</strong> <code>8 → Women</code>
</p>

<hr>

<h2>📌 Key Features</h2>
<ul>
  <li>No deep learning — purely ML-based</li>
  <li>StandardScaler applied correctly (fit only on train data)</li>
  <li>Supports real-world single image predictions</li>
  <li>Fast training and testing</li>
</ul>

<hr>

<h2>🧪 Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>scikit-learn</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>OpenCV or PIL (for image loading)</li>
</ul>

<hr>

<h2>📁 Files in This Repository</h2>
<ul>
  <li><code>Image Modeling.ipynb</code> — Full notebook including individual image testing</li>
  <li><code>/sample_images</code> — Images used for prediction (optional)</li>
  <li><code>model.pkl</code> (optional) — Saved trained model</li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>
<p>
<strong>Teemara Sai</strong><br>
💡 Interested in Machine Learning, Computer Vision & Data Analysis
</p>
