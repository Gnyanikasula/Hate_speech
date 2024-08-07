# Hate-Speech and Offensive Language Detection in Roman Urdu

## Project Description

This project focuses on detecting hate speech and offensive language in Roman Urdu using a fine-tuned "bert-base-multilingual-uncased" transformer model. The dataset comprises 7,209 social media comments in Roman Urdu.

## Models Used

- **BERT Multilingual (uncased)**: Fine-tuned for the task of hate speech detection.

The model achieved an accuracy of nearly 73%, despite the challenges of not using a specific Roman Urdu embedding space and limited advanced resources.

## Repository Contents

- `BERT_Roman.ipynb`: Jupyter Notebook containing the implementation details, data cleaning process, and model training.

## Results

The model categorizes comments into 5 categories, achieving an accuracy rate of nearly 73%.

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/Gnyanikasula/Hate_speech.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Hate_speech
   ```
3. Open the Jupyter Notebook to explore the code and results:
   - `BERT_Roman.ipynb`

## Future Work

- Fine-tuning the model with more specific Roman Urdu embeddings.
- Increasing the dataset size and diversity.
- Incorporating more advanced NLP techniques for better performance.

## Contact

For any inquiries or contributions, please reach out via [GitHub Issues](https://github.com/Gnyanikasula/Hate_speech/issues).
