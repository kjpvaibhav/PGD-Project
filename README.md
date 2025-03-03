# Multi Class Classification on Retinal Eye Diseases using Swin Transformer

## Abstract
Retinal eye diseases are among the leading causes of vision impairment globally, with various conditions such as diabetic retinopathy, age related macular degeneration, and glaucoma requiring accurate and early diagnosis. In this project, I propose a multi-class classification framework to identify and classify different retinal diseases using the Swin Transformer, a state-of-the-art vision transformer model. We leverage the ODIR-5K dataset, which contains images of retinal fundus, along with their corresponding diagnostic labels. By employing the Swin Transformer model, known for its hierarchical feature extraction capabilities and efficient handling of high-resolution images, I aim to improve the accuracy of disease detection in retinal scans.

We begin by preprocessing the dataset, including augmenting the images to enhance model generalization, and applying label encoding to categorize eight distinct classes of retinal diseases. My approach utilizes a deep learning pipeline incorporating transfer learning with a pre-trained Swin Transformer model, optimizing the network with class-weighted loss functions to account for class imbalances. Extensive training, validation, and evaluation metrics such as accuracy, precision, recall, F1 score, ROC AUC, and Cohen’s Kappa are computed to assess the model’s performance. I demonstrated that my model achieves competitive performance in terms of classification accuracy and generalization, showing its potential for real-world applications in ophthalmology, providing timely and accurate diagnosis of retinal diseases and assisting healthcare professionals in their decision-making processes.

The results indicate that the Swin Transformer model can significantly
enhance the diagnostic capability for retinal diseases, offering a
robust tool for automated medical image analysis and contributing to the
advancement of AI-driven healthcare solutions.
