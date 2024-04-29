English-to-Hindi-Machine-Translation
NLP-DSCI-6004-02 Project

Team Members:
Shaik Adil
Sneha Reddy Vangala
Komal Tankashala

Summary
Contained within this repository are the code and documentation for our NLP-DSCI-6004-01 project, which concentrates on an inventive method for translating English to Hindi. By leveraging cutting-edge techniques in natural language processing (NLP) and deep learning, our model aims to tackle the challenges inherent in cross-language translation. This project offers a comprehensive overview, encompassing motivation, technical specifics, training optimization, and extensive evaluation.

Contents
1. Introduction:
Overview of the project's focus on translating English to Hindi using machine translation.
Highlights the importance of overcoming language barriers through automated translation.
2. Related Work:
Examines the use of Seq2Seq models, beginning with the foundational work of Sutskever et al.
Explores advancements such as attention mechanisms, Transformer models, transfer learning, and domain adaptation in English-to-Hindi translation.
3. Methodology:
2. Data Collection:
Manual extraction from the Yale website followed by translation using Google Translate.
Creation of a dataset comprising 128 samples for English-to-Hindi translation.
3. Data Processing:
Preprocessing involving the creation of dictionaries and necessary transformations.
Calculation of vocabulary sizes for both English and Hindi.
4. Custom Dataset Creation:
Development of a custom dataset class for model training.
An illustrative example demonstrating English and Hindi sentences with tensor representations.
5. Data Loading:
Partitioning the dataset into training, testing, and validation subsets.
Implementation of PyTorch DataLoader with a collate function for efficient loading.
6. Model:
Adoption of the pretrained MarianMTModel with an encoder-decoder architecture.
Explanation of the model's components, including encoder layers, decoder layers, and positional embeddings.
7. Training and Fine-Tuning Hyperparameters:
Comprehensive training loop with functions for optimization and evaluation.
Fine-tuning experiments for learning rates and momentum rates.
8. Simulation and Results:
Visual representation of training and validation loss over epochs for learning rate and momentum rate tuning.
Discussion of the BLEU score of 0.23 as an evaluation metric, indicating reasonable translation accuracy.
9. Tokenization:
Implementation of tokenization using the transformers library.
Explanation of key steps, including padding, truncation, and conversion to PyTorch tensors.
10. Conclusion:
Reflection on the project's contribution to English-to-Hindi translation and broader machine translation research.
Acknowledgment of challenges and proposed avenues for future work, highlighting insights gained from pre-trained models.
Contribution Guidelines
If you wish to contribute to the project, adhere to the following guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Implement your changes and commit them.
Push your changes to your fork.
Submit a pull request, detailing the modifications made and providing relevant context.
License
This project is licensed under the MIT License.

Acknowledgments
We extend our gratitude to the entire team and the supportive community for their contributions.
