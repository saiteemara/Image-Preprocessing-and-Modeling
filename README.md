<h1>🖼️ Image Classification Using KNN & Random Forest</h1>

<h2>🔍 Overview</h2>
<p>
This project performs <strong>image classification</strong> using traditional Machine Learning models 
instead of deep learning. Images are flattened and converted into numerical feature vectors, 
scaled using StandardScaler, and classified using <strong>K-Nearest Neighbors (KNN)</strong> 
and <strong>Random Forest</strong> algorithms.
</p>

<hr>

<h2>🎯 Project Objectives</h2>
<ul>
  <li>Load and preprocess image dataset</li>
  <li>Convert images into a structured feature matrix</li>
  <li>Apply StandardScaler for normalization</li>
  <li>Train and evaluate ML models (KNN & RandomForest)</li>
  <li>Test the model on individual images</li>
</ul>

<hr>

<h2>📂 Workflow</h2>
<ol>
  <li><strong>Load Dataset</strong> and create DataFrame</li>
  <li><strong>Split</strong> into train and test sets</li>
  <li><strong>Scale features</strong> using StandardScaler</li>
  <li>Train models:
    <ul>
      <li>K-Nearest Neighbors (KNN)</li>
      <li>RandomForest Classifier</li>
    </ul>
  </li>
  <li>Evaluate accuracy</li>
  <li>Perform <strong>sample testing</strong> and <strong>individual image prediction</strong></li>
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
✅ RandomForest performed significantly better than KNN due to robustness with high-dimensional image data.
</p>

<hr>

<h2>🧠 Why No Deep Learning?</h2>
<ul>
  <li>Focus on classical ML approach</li>
  <li>Small dataset suitable for non-DL models</li>
  <li>Faster training without GPU requirement</li>
</ul>

<hr>

<h2>📌 Features</h2>
<ul>
  <li>End-to-end image processing pipeline</li>
  <li>StandardScaler applied only to training data</li>
  <li>Supports prediction on new images</li>
  <li>Clean and simple ML-based implementation</li>
</ul>

<hr>

<h2>📁 Files in This Repository</h2>
<ul>
  <li><code>Image Modeling.ipynb</code> — Full notebook with preprocessing, training & testing</li>
  <li><code>/sample_images</code> — Optional testing images</li>
  <li><code>requirements.txt</code> (optional)</li>
</ul>

<hr>

<h2>👩‍💻 Author</h2>
<p>
<strong>Teemara Sai</strong><br>
💡 Interested in Machine Learning, Computer Vision & Data Analysis
</p>
