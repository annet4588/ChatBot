# ChatBot App

This ChatBot app is an interactive application that uses Natural Language Processing (NLP) and machine learning to understand and respond to user inputs. It is designed to simulate human-like conversations based on predefined intents.

## Features

- **Natural Language Understanding**: Interprets user inputs and matches them with predefined intents.
- **Conversational AI**: Maintains a smooth flow of conversation by understanding context and providing appropriate responses.
- **Customizable**: Easily add new intents and responses to tailor the chatbot to specific needs.
- **User-Friendly**: Simple and intuitive interface for easy interaction.

## Setup

### Prerequisites

- [Python 3.x](https://www.python.org/downloads/)
- [NLTK](https://www.nltk.org/)
- [NumPy](https://numpy.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [TFLearn](http://tflearn.org/)
- JSON
- Pickle

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/chatbot-app.git
    cd chatbot-app
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv myenv
    source myenv/bin/activate   # On Windows use `myenv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    pip install nltk numpy tensorflow tflearn
    ```

4. **Download NLTK data**:
    ```python
    import nltk
    nltk.download('punkt')
    ```

## Contributing

Contributions are welcome! Please feel free to submit a [Pull Request](https://github.com/yourusername/chatbot-app/pulls).

## License

This project is licensed under the [MIT License](LICENSE). See the LICENSE file for details.
