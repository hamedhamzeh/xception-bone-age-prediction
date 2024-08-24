<h1>Pediatric Bone Age Prediction Using Xception Model</h1>

<p>This repository contains the code and model for predicting bone age from hand X-ray images using an Xception architecture.
    The model was trained on the RSNA Pediatric Bone Age dataset, available on Kaggle, using a T4 GPU.</p>

<h2>Project Overview</h2>
<ul>
    <li><strong>Objective:</strong> To predict the bone age of pediatric patients using hand X-ray images with a focus on accuracy and robustness.</li>
    <li><strong>Dataset:</strong> <a href="https://www.kaggle.com/kmader/rsna-bone-age" target="_blank">RSNA Pediatric Bone Age Dataset</a> from Kaggle.</li>
    <li><strong>Model Architecture:</strong> The Xception model, known for its efficiency and performance in image classification tasks, is employed in this project.</li>
    <li><strong>Performance:</strong> The model achieves a training error of approximately 4.9 months and a validation error of 9.1 months, demonstrating its ability to estimate bone age with reasonable accuracy.</li>
    <li><strong>Monitoring:</strong> Model performance was tracked and monitored using <a href="https://wandb.ai/" target="_blank">Weights & Biases (WANDB)</a> throughout the training process.</li>
    <li><strong>pre-trained model:</strong> You can download the pre-trained model from <a href="https://www.kaggle.com/datasets/hamedhamzeh/best-model-trained-keras" target="_blank">here</a></li>
</ul>

<h2>Features</h2>
<ul>
    <li><strong>Data Augmentation:</strong> Techniques such as image resizing, normalization, and augmentation are applied to improve model robustness.</li>
    <li><strong>Visualization:</strong> Includes plots and visualizations that depict the model's performance and error distribution.</li>
</ul>

<h2>Model Output Example</h2>
<p>Below is examples of the model’s output, showing the predicted bone age compared to the actual bone age:</p>
<img src="https://github.com/hamedhamzeh/xception-bone-age-prediction/blob/main/output%20images/ouput2.JPG" alt="Model Output Example" width="600">
<img src="https://github.com/hamedhamzeh/xception-bone-age-prediction/blob/main/output%20images/ouput1.JPG" alt="Model Output Example" width="600">
