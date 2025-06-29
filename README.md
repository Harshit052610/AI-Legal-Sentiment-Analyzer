# AI Legal Sentiment Analyzer

## Overview
The AI Legal Sentiment Analyzer is a Python-based tool designed to classify the sentiment of legal texts as Positive, Negative, or Neutral. This project leverages the FLAN-T5 model from the Hugging Face Transformers library, running on Google Colab or a local environment with GPU support. The tool has been enhanced to accept user input interactively, process it, and save the results to a CSV file.

## Features
- Analyzes legal text sentiment using the FLAN-T5 model.
- Accepts user-provided text input for real-time sentiment analysis.
- Generates a CSV output file with predicted and expected sentiments.
- Supports both command-line and interactive usage.
- Includes error handling for robust operation.

## Installation

### Prerequisites
- Python 3.7 or higher
- Git (for cloning the repository)
- A compatible environment with GPU support (optional but recommended)

### Steps
1. Clone the repository:
2. - Use `--delimiter "\t"` if your CSV is tab-separated.

## Project Structure
AI_Legal_Sentiment_Analyzer/
├── src/                # Source code
│   └── sentiment_analyzer.py  # Main script with interactive and batch modes
├── data/               # Datasets and output files
│   ├── custom_legal_dataset.csv  # Input dataset with 25 legal texts
│   └── legal_output1.csv  # Output file with analysis results
├── notebooks/          # Jupyter/Colab notebooks
│   └── AI_Legal_Sentiment_Analyzer.ipynb  # Colab notebook for the project
├── docs/               # Documentation
│   └── AI_Legal_Sentiment_Analyzer_Report.pdf  # Project report
├── requirements.txt    # Python dependencies
├── README.md           # This file
└── .gitignore          # Ignored files (e.g., venv/, *.pyc)

## Development
- **Code Updates**: The script now supports interactive input. Contributions to add features (e.g., web interface, more sentiment categories) are welcome.
- **Branching**: Use a `develop` branch for new features: `git checkout -b develop`.
- **Pull Requests**: Submit changes via pull requests to the `main` branch.

## Testing
- Test interactively: `python src/Ai Legal sentiment.py --interactive` with sample inputs.
- Test with dataset: `python src/Ai Legal sentiment.py --input_csv data/custom_legal_dataset(1).csv`.
- Verify output in `data/predicted_output.csv` matches expected sentiments.

## Contact
- **Author**: [N HARSHIT]   
- **Issues**: Report bugs or suggestions on the [GitHub Issues page](https://github.com/Harshit052610/AI_Legal_Sentiment_Analyzer/issues).

## Acknowledgments
- Hugging Face Transformers for the FLAN-T5 model.
- Google Colab for the development environment.
- [Your Name] for development and enhancements.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
