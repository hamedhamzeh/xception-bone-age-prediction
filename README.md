<h1>Pediatric Bone Age Prediction Using Xception Model</h1>

<p>This repository contains the code and model for predicting bone age from hand X-ray images using an Xception architecture. The model was trained on the RSNA Pediatric Bone Age dataset, available on Kaggle, using a T4 GPU.</p>

<h2>Project Overview</h2>
<ul>
    <li><strong>Objective:</strong> To accurately predict the bone age of pediatric patients from hand X-ray images.</li>
    <li><strong>Dataset:</strong> <a href="https://www.kaggle.com/kmader/rsna-bone-age" target="_blank">RSNA Pediatric Bone Age Dataset</a> (available on Kaggle).</li>
    <li><strong>Model Architecture:</strong> Xception, a deep convolutional neural network designed for high-performance image classification tasks.</li>
    <li><strong>Training Performance:</strong>
        <ul>
            <li>Best training set error: <strong>4.9 months</strong></li>
            <li>Best validation set error: <strong>9.1 months</strong></li>
            <li>These results indicate that the model can predict the bone age with an average error of approximately 4.9 months on the training set and 9.1 months on the validation set.</li>
        </ul>
    </li>
</ul>

<h2>Features</h2>
<ul>
    <li><strong>Preprocessing:</strong> Includes data augmentation and normalization techniques to improve model robustness.</li>
    <li><strong>Training:</strong> Utilized a Kaggle T4 GPU to efficiently train the Xception model.</li>
    <li><strong>Evaluation:</strong> Provides a comprehensive analysis of the model's performance, including error metrics and visualizations.</li>
</ul>

<h2>Usage</h2>
<p>Instructions on how to use the model and code can be found in the <a href="README.md">README</a> file.</p>
