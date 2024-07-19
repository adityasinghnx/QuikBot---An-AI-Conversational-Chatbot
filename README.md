# QuikBot

QuikBot is a basic AI conversational chatbot created using Gemini Pro and Streamlit. It can maintain chat history, providing a smooth and interactive user experience.

## Features

- **Advanced Generative Capabilities**: Built with Gemini Pro.
- **User-Friendly Interface**: Integrated with Streamlit.
- **Chat History**: Maintains conversation context for a seamless experience.

## Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/QuikBot.git
    cd QuikBot
    ```

2. **Create and activate a virtual environment:**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables:**
    - Create a `.env` file in the project root directory.
    - Add your Google API key to the `.env` file:
    ```sh
    GOOGLE_API_KEY=your_google_api_key
    ```

## Usage

1. **Run the Streamlit app:**
    ```sh
    streamlit run app.py
    ```

2. **Interact with QuikBot:**
    - Open your web browser and navigate to `http://localhost:8501`.
    - Enter your queries in the input box and press "Submit" to receive responses from QuikBot.

## Project Structure

- `app.py`: The main application file containing the Streamlit app and chatbot logic.
- `requirements.txt`: List of Python dependencies required for the project.
- `.env`: File to store environment variables (not included in the repository for security reasons).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## Contact

If you have any questions or feedback, feel free to reach out.

---

Enjoy using QuikBot! 🚀
