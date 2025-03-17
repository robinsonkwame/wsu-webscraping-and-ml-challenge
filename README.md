# Web Scraping and Image Classification Challenge: Finding Cats on a Webpage!

## Introduction

This is a short programming challenge designed to test your basic Python skills, including setting up a virtual environment, web scraping, and using a pre-trained machine learning model for image classification.

## Task

Your task is to write a Python script that does the following:

1.  **Set up a virtual environment:** Create a virtual environment for your project to manage dependencies.
2.  **Install dependencies:** For example, use `pip` and a `requirements.txt` file to install the necessary Python libraries.
3.  **Web scrape a cat image URL:** Programmatically push "Give me a cat," or otherwise fetch a random cat image, from [https://cataas.com/](https://cataas.com/).
4.  **Download the image:** Download the image from the fetched URL.
5.  **Classify the image:** Use a pre-trained cat/not-cat classification model to determine if the downloaded image is a cat or not. We suggest using the [jake2004/Varun_cat-model2](https://huggingface.co/jake2004/Varun_cat-model2) model from Hugging Face.
6.  **Output the result:** Print to the console whether the image is classified as a "cat" or "not cat".

## Submission

Please fork this project and commit the following to your respository:

*   Your Python script (e.g., `classify_cat.py`).
*   A `requirements.txt` file listing all the Python libraries your script depends on.
*   Send an email to us that you've done so

## Bonus (Optional)

*   Handle potential errors gracefully (e.g., network issues, model loading errors).
*   Add comments to your code to explain your approach.

## Getting Started and How your Fork will be Tested

1.  **Clone this repository (if applicable) or create a new directory.**
2.  **Create a virtual environment:**
    ```bash
    python -m venv venv
    ```
    ```bash
    # On Windows:
    venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```
3.  **Create a `requirements.txt` file**
4.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
5.  **Write your Python script** (e.g., `classify_cat.py`) to solve the task.
6.  **Run your script:**
    ```bash
    python classify_cat.py
    ```

Good luck! 
