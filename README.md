# English-to-Hinglish-Tanslation_Model
Translate English sentences to Hinglish using NLTK and Google Translate

# overview 
This repository contains a Python script that translates English sentences to Hinglish (a mixture of Hindi and English). The translated text aims to sound natural and be easily understood by both native Hindi speakers and non-native Hindi speakers.

# Project Goals
This project focuses on achieving the following objectives:

1. **Natural Translation**: Develop a translation model capable of generating Hinglish text that closely resembles spoken Hindi language patterns.

2. **Clarity and Retention**: Retain certain English words to improve clarity, especially for non-native Hindi speakers.

3. **Meaning Accuracy**: Ensure that the Hinglish translations accurately convey the meaning of the original English sentences.


# Libraries Used

- **NLTK (Natural Language Toolkit)**: Used for text processing, including noun extraction.
- **Google Translate API**: Employed for translating English text into Hindi.

# Code Components
The project code within this repository encompasses the following key components and functionalities:

1. **Translation Model**: This core component utilizes NLTK for text processing and leverages the Google Translate API to convert English sentences into Hinglish.

2. **Noun Extraction**: We have included a function that identifies and extracts nouns from input sentences using NLTK.

3. **Translation Function**: Another function makes use of the Google Translate API to translate English sentences into Hindi.

4. **Replacement Logic**: The project includes a function for replacing nouns in the Hindi translation with their English counterparts, while still retaining certain words in English for clarity.

# Getting Started
Here's a step-by-step guide on how to use the code:
1. **Clone the Repository**: Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/YashaswiniJawalkar/English-to-Hinglish-Tanslation_Model.git
   
2. **Install Dependencies**: Ensure Python is installed on your system. If not, you can download it from python.org. Afterward, install the necessary Python libraries by running these commands:

    ```bash
    !pip install nltk
    !pip install googletrans==4.0.0-rc1
    
3. **Run the Code**: Execute the code to translate English text into Hinglish. Customize the input text and other options as needed.

# sample Output

- **Enter a sentence**: I had about a 30 minute demo just using this new headset
- **Hinglish Sentence**: मेरे पास इस नए headset का उपयोग करके लगभग 30 minute का demo था
- **Enter a sentence**: Definitely share your feedback in the comment section.
- **Hinglish Sentence**: निश्चित रूप से comment section में अपनी feedback साझा करें।
