# Country_Language

This repository contains a Jupyter Notebook project that integrates with OpenAI's API to perform language-based tasks, with potential use cases such as analyzing or processing language and multimedia content.

## Features

- **OpenAI Integration**: Uses OpenAI API for language or AI-driven tasks.
- **Gradio Interface**: Implements a user-friendly graphical interface for interaction.
- **Audio and Image Processing**: Supports handling audio files (via PyDub) and images (via PIL).
- **Environment Configuration**: Reads and validates API keys from `.env` files.

## Requirements

To run this notebook, ensure the following dependencies are installed:

- Python 3.8 or higher
- Libraries: `openai`, `gradio`, `pydub`, `Pillow`, `python-dotenv`, and `IPython`

You can install all dependencies using:

```bash
pip install openai gradio pydub Pillow python-dotenv ipython
```

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Mjaddour/Country-Language.git
   cd Country_Language
   ```

2. Create a `.env` file in the project root and add your OpenAI API key:

   ```env
   OPENAI_API_KEY=your_openai_api_key
   ```

3. Launch the Jupyter Notebook:

   ```bash
   jupyter notebook Country_Language.ipynb
   ```

## Usage

- Follow the code cells in the notebook sequentially to set up and execute tasks.
- The Gradio UI provides a simple interface for user interaction, allowing easy testing and demonstration.

## Sample Workflow

1. **Initialize API**: Ensure your OpenAI API key is loaded and accessible.
2. **Run Gradio UI**: Start the Gradio interface to interact with the project.
3. **Process Media**: Utilize features for processing audio and images as needed.

## Examples
![image](https://github.com/user-attachments/assets/2fc53539-9d33-4780-bb67-961a668aeba5)
![image](https://github.com/user-attachments/assets/08fc22da-0b94-4b5f-a7bd-7ce599c97b16)

