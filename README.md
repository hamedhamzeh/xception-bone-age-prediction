<h1>Pediatric Bone Age Prediction Using Xception Model</h1>

<p>This repository contains a Jupyter Notebook that demonstrates the process of predicting pediatric bone age from hand X-ray images using the Xception deep learning model. The project is built upon the RSNA Pediatric Bone Age dataset, utilizing a Kaggle T4 GPU for training.</p>

<h2>Project Overview</h2>
<ul>
    <li><strong>Objective:</strong> To predict the bone age of pediatric patients using hand X-ray images with a focus on accuracy and robustness.</li>
    <li><strong>Dataset:</strong> <a href="https://www.kaggle.com/kmader/rsna-bone-age" target="_blank">RSNA Pediatric Bone Age Dataset</a> from Kaggle.</li>
    <li><strong>Model Architecture:</strong> The Xception model, known for its efficiency and performance in image classification tasks, is employed in this project.</li>
    <li><strong>Performance:</strong> The model achieves a training error of approximately 4.9 months and a validation error of 9.1 months, demonstrating its ability to estimate bone age with reasonable accuracy.</li>
    <li><strong>Monitoring:</strong> Model performance was tracked and monitored using <a href="https://wandb.ai/" target="_blank">Weights & Biases (WANDB)</a> throughout the training process.</li>
</ul>

<h2>Key Steps in the Notebook</h2>
<ul>
    <li><strong>Importing Libraries:</strong> The project begins by importing essential libraries such as TensorFlow, Pandas, OpenCV, and Matplotlib.</li>
    <li><strong>Data Loading:</strong> The RSNA Pediatric Bone Age dataset is loaded and preprocessed for training.</li>
    <li><strong>Model Training:</strong> The Xception model is trained on the dataset using a T4 GPU, with various hyperparameters tuned for optimal performance.</li>
    <li><strong>Evaluation:</strong> The model's performance is evaluated, and results are visualized to assess its accuracy.</li>
</ul>

<h2>Features</h2>
<ul>
    <li><strong>Data Augmentation:</strong> Techniques such as image resizing, normalization, and augmentation are applied to improve model robustness.</li>
    <li><strong>Visualization:</strong> Includes plots and visualizations that depict the model's performance and error distribution.</li>
</ul>

<h2>Model Output Example</h2>
<p>Below is an example of the model’s output, showing the predicted bone age compared to the actual bone age:</p>
<img src="path_to_your_image.png" alt="Model Output Example" width="600">

<h2>How to Run</h2>
<p>
    <ol>
        <li>Clone the repository.</li>
        <li>Ensure that all required libraries are installed (a <code>requirements.txt</code> file may be provided).</li>
        <li>Open the Jupyter Notebook and follow along with the code cells to reproduce the results.</li>
    </ol>
</p>
