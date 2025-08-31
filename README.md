# AI Legal Sentiment Analyzer ⚖️
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)



## Overview 🚀
The AI Legal Sentiment Analyzer is a Python-based tool designed to classify the sentiment of legal texts as Positive 👍, Negative 👎, or Neutral 😐. This project leverages the FLAN-T5 model from the Hugging Face Transformers library. It's enhanced to accept user input interactively, process it, and save the results to a CSV file.



## Table of Contents 📚
1.  [Features](#features)
2.  [Tech Stack](#tech-stack)
3.  [Installation](#installation)
4.  [Usage](#usage)
5.  [How to Use](#how-to-use)
6.  [Project Structure](#project-structure)
7.  [Contributing](#contributing)
8.  [License](#license)
9.  [Important Links](#important-links)
10. [Footer](#footer)



## Features ✨
-   **Sentiment Analysis**: Utilizes the FLAN-T5 model for classifying legal text sentiment.
-   **Interactive Input**: Accepts user-provided text for real-time sentiment analysis.
-   **CSV Output**: Generates a CSV file with predicted and expected sentiments.
-   **Command-Line Support**: Supports both command-line and interactive usage.
-   **Error Handling**: Includes error handling for robust operation.



## Tech Stack 💻
-   Python
-   Transformers (Hugging Face)
-   Pandas
-   Torch
-   Jupyter Notebook



## Installation 🛠️



### Prerequisites
-   Python 3.7+
-   Git (for cloning the repository)



### Steps
1.  Clone the repository:

    ```bash
    git clone https://github.com/Harshit052610/AI-Legal-Sentiment-Analyzer.git
    cd AI-Legal-Sentiment-Analyzer
    ```

2.  Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```



## Usage 💡
This project can be used in two ways: interactively or with a dataset.



### Interactive Mode
Run the script in interactive mode to analyze the sentiment of text you provide in real-time.

```bash
python src/Ai Legal sentiment.py --interactive
```



### Dataset Mode
Run the script with an input CSV file to analyze the sentiment of multiple texts at once.

```bash
python src/Ai Legal sentiment.py --input_csv data/custom_legal_dataset\(1\).csv
```



## How to Use 🧑‍⚖️
This tool is designed to analyze the sentiment of legal texts. Here are a few real-world use cases:

-   **Legal Document Review**: Quickly assess the overall sentiment of contracts, court filings, and other legal documents.
-   **Client Feedback Analysis**: Understand client sentiment from feedback forms or surveys.
-   **Risk Assessment**: Identify potentially negative sentiments in legal communications to mitigate risks.

To use the project:

1.  Ensure you have installed all the dependencies using `pip install -r requirements.txt`.
2.  Run the script in either interactive or dataset mode, as shown in the Usage section.
3.  Check the output CSV file in the `data/` directory for the analysis results.



## Project Structure 📂
```
AI_Legal_Sentiment_Analyzer/
├── src/                        # Source code
│   └── Ai Legal sentiment.py   # Main script with interactive and batch modes
├── data/                       # Datasets and output files
│   └── custom_legal_dataset (1).csv # Input dataset with legal texts
├── notebooks/                  # Jupyter/Colab notebooks
│   └── Ai_Legal_sentiment.ipynb # Colab notebook for the project
├── requirements.txt            # Python dependencies
├── README.md                   # This file
└── .gitignore                  # Ignored files
```



## Contributing 🤝
Contributions are welcome! Here's how you can contribute:

-   Fork the repository.
-   Create a new branch for your feature or bug fix.
-   Submit a pull request.



## License 📄
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## Important Links 🔗
-   **Repository**: [https://github.com/Harshit052610/AI-Legal-Sentiment-Analyzer](https://github.com/Harshit052610/AI-Legal-Sentiment-Analyzer)



## Footer 📝
AI-Legal-Sentiment-Analyzer - [https://github.com/Harshit052610/AI-Legal-Sentiment-Analyzer](https://github.com/Harshit052610/AI-Legal-Sentiment-Analyzer) by [N HARSHIT]

⭐ Give a star to this project on [GitHub](https://github.com/Harshit052610/AI-Legal-Sentiment-Analyzer)!

⚖️ Fork the repository, contribute, and raise issues to enhance this AI Legal Sentiment Analyzer!
