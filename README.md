# FOODIMI
FOODiMi - Your Smart Recipe Buddy 🧑‍🍳

FOODiMi is a dynamic web application built with Flask and the Gemini API that allows users to generate custom recipes based on a selection of available ingredients and specific dietary or style prompts.

The application features a modern, dark-themed, and responsive GUI, making it easy to select ingredients and quickly generate creative meal ideas.

✨ Features

Ingredient Selection: Choose from a wide variety of raw materials categorized into groups (fruits, vegetables, grains, spices, etc.).

Custom Prompting: Add specific instructions (e.g., "spicy curry," "healthy breakfast," "vegan dinner") to guide the AI-generated recipe.

AI-Powered Recipes: Leverages the Gemini API (gemini-2.5-flash) to generate detailed recipes in real-time.

Attractive UI: Features a dark, responsive layout designed with a focus on user experience.

🛠️ **Tech Stack**

* **Backend Framework:** Python (Flask)
* **AI Model:** Gemini 2.5 Flash (via `google-genai` SDK)
* **Frontend:** HTML5, CSS3
* **Dependencies:** `python-dotenv`, `markdown2`, `Flask`

🛠️ **Setup and Installation**

Prerequisites:
You need Python 3.8 installed on your system.

Steps:
Clone the Repository:

    cd /path/to/foodimi
    ```
Create environment:

    python -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # venv\Scripts\activate   # On Windows
    ```

Install Dependencies:

    pip install Flask google-genai python-dotenv markdown2
    ```


Configure API Key:
The application requires a Gemini API Key to function. Create a file named **.env** in the root directory of your project and add your API key:


    GEMINI_API="YOUR_API_KEY_HERE"
    ```

*You can obtain a key from Google AI Studio.

🚀 Usage:
To run the application, execute the main.py file:

     python main.py


The Flask server will start, typically running on http://127.0.0.1:5000/.

📂 **Project Structure**

| File | Description |
| :--- | :--- |
| `main.py` | 
| `templates/template.html` |
| `static/style.css` | 
| `static/pics/` | 
| `.env` | Stores the secret `GEMINI_API` key. |

**How to Generate a Recipe🍳**:

Select Ingredients: Use the sidebar on the right to expand categories and check the ingredients you have available.

Enter a Prompt (Optional but Recommended): Type your desired meal type, cuisine, or restrictions (e.g., "quick lunch", "Italian style", "low carb").

Generate: Click the "Generate Recipe" button. The application will send your selections to the Gemini model, and the resulting recipe will appear in the output section.


🤝 Contribution

 Feel free to use and modify it for learning purposes.

📝 License

This project is open-source.
