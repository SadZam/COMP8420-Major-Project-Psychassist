# COMP8420-Major-Project-Psychassist

# Emotion Recognition for PsychAssist

## Project Overview
This project implements an emotion recognition system designed for PsychAssist, leveraging advanced natural language processing (NLP) techniques and pre-trained transformer models from Hugging Face. The objective is to identify and analyze emotions expressed in text data, enabling better understanding and management of mental health issues.

## Table of Contents
- [Installation](#installation)
- [COMP8420_MajorProject_Psychassist ](#COMP8420_MajorProject_Psychassist )
- [Model Selection](#model-selection)
- [Contributing](#contributing)
- [License](#license)

## Installation
To set up this project, follow these steps:

1. **Clone the repository:**
   

2. **Create and activate a virtual environment:**
   

3. **Install the required packages:**
   

## Jupyter file - COMP8420_MajorProject_Psychassist 
1. **Load the dataset:**
    Ensure your dataset is in the same directory as your script, named `mentalhealth_data.csv`.

## Model Selection 
This project uses multiple pre-trained models from Hugging Face for emotion recognition and for text summarisation: 
*Emotion-Specific Models:* 
- j-hartmann/emotion-english-distilroberta-base
-  SamLowe/roberta-base-go_emotions
-   oeddav/distilbert-base-uncased-go-emotions-student
-  bhadresh-savani/distilbert-base-uncased-emotion *Text Summarisation Models* 
y


3. **Preprocess the data:**
    Clean and preprocess the text data by removing special characters, stopwords, and performing lemmatization. Generate sentiment labels using the VADER sentiment analyzer. Shown in the notebook.

4. Model Selection
   This project uses multiple pre-trained models from Hugging Face for emotion recognition and for text summarisation:

 **Emotion-Specific Models:**
    - `j-hartmann/emotion-english-distilroberta-base`
    - `SamLowe/roberta-base-go_emotions`
    - `joeddav/distilbert-base-uncased-go-emotions-student`
    - `bhadresh-savani/distilbert-base-uncased-emotion`
  
**Text Summarisation Models**
  - Bart has been used
  - BART was Chosen for its proficiency in generating accurate and coherent summaries   
-  Known for effective summarization of complex and lengthy texts.
-   Adapts well to various text types and summarization needs.
-    Easily integrates with Hugging Face's Transformers librar
4.**Results**
    Qualitative comparison and human evaluation to select goodperforming models.
    then we fine-tuned 2 models to get the one wih maximum accuracy.
    


## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for using the project for PsychAssist! For any questions or issues, please open an issue in the repository or contact the maintainers.
