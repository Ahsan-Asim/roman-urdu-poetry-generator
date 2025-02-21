# Poetry Generation Project

This project explores the creation of poetry using LSTM. The goal is to generate human-like, creative poems based on first line of poem.

## Project demo 

![Alt text](images/demo.jpg)


## Project Overview

The Poetry Generation Project leverages deep learning models to generate creative, meaningful poems based on user-provided input. It utilizes advanced NLP models to understand and generate verses, stanzas, and rhymes, creating poetry that mimics human-like creativity.

## Key Features

- **Creative Poetry Generation**: Generate poems from a variety of themes and prompts, such as love, nature, and life.
- **Customizable Output**: Users can specify a length, and the model will adapt its output.
- **User Interaction**: Allows users to interactively input prompts and get generated poems in real-time.

## Technologies Used

- **Python**: Primary programming language for NLP and machine learning models.
- **PyTorch**: Deep learning frameworks for training models (if applicable).
- **NLTK**: For natural language processing tasks such as tokenization, part-of-speech tagging, and more.
- **Streamlit**: For creating a web interface or interactive platform for poem generation.

## Setup Instructions

1. Clone the repository:

    ```bash
    git clone https://github.com/zuhairzaidi63/roman-urdu-poetry-generator.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Alternatively, if you're using a web interface:

    ```bash
    streamlit run app.py
    ```

4. Enter a theme or prompt when prompted, and the model will generate a poem.

## Example Usage

1. Input a prompt like:

    > "aañkh se duur na ho dil"

    The system will then generate a poem based on this input.

##  Project Structure

```
├── .devcontainer/            # Dev Container configuration files
├── dataset/                  # Contains datasets used for training the model
├── Poetry_Generation_Task.ipynb  # Jupyter Notebook for poetry generation
├── README.md                 # Project documentation
├── app.py                    # Main application script
├── dataset.zip               # Compressed dataset file
├── poetry_lstm_model.pth     # Trained LSTM model file
├── requirements.txt          # Dependencies required to run the project
└── simple_vocab.pkl          # Vocabulary file for text processing
```
## 🌐 Live Demo  
Check out the deployed version of this project:  
🔗 [Live Website](https://ghazalbot.streamlit.app/)

## Contributing

Feel free to contribute to this project! If you have any ideas for improvements, bug fixes, or additional features, fork the repository, make your changes, and submit a pull request.

## Blog  
I have documented the process of building this project which you can read by clicking below:  
🔗 [Read the Blog](https://medium.com/@zuhair.zaidi407/ai-powered-roman-urdu-poetry-generation-with-lstms-and-streamlit-afc0903f3623)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


For any questions or issues, please feel free to open an issue on the GitHub repository.
