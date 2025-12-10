# Infinite Homework AI

A tool that uses AI to generate infinite, randomized printable homework packets (PDFs) for students. Your students are going to love you!

## Features

Leveraging Google's Gemini AI (Flash v2.5, but you can switch the model), this tool lets you generate personalized homework packets for multiple students at once—selecting from a wide range of topics like fractions, equations, and geometry for grades 4 through 7—and automatically outputs ready-to-print PDF worksheets with a corresponding answer key.

## Quick Start (Google Colab)

1.  **Open the Notebook** in Google Colab.
2.  **Add your API Key:**
    * Get a free key from [Google AI Studio](https://aistudio.google.com/).
    * In Colab, go to the **Secrets** tab (key icon on the left), add a new secret named `GEMINI_API_KEY`, and toggle "Notebook access" on.
3.  **Configure:**
    * Enter child names (e.g., `Alice, Bob`) in the form field.
    * Select the grade level and number of questions.
    * Check/Uncheck the specific math topics you want to include.
4.  **Run:** Click "Runtime" > "Run all". The PDFs will download automatically.

## Notes

* **Model Selection:** The script defaults to `gemini-2.5-flash`, but feel free to change the model definition in the code to your favorite version.
* **Billing & Rate Limits:** It is recommended to link your API Key project to a Google Cloud billing account. Without it, you may encounter Rate Limit (429) errors, as this script does not implement proactive throttling.

## Requirements

* Google Account (for Colab access)
* Google Gemini API Key (Free)

## License

MIT License