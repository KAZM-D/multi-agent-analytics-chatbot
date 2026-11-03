> **Note:** This project was built and run in Google Colab (it uses Colab-specific modules like `google.colab.output`). It is not currently set up to run as a standalone local app — running the `.py` files directly outside Colab will require adapting the Colab-specific parts.

If running in Colab:

1. **Set your API keys** — open `chatbotG2.ipynb` and set the following as environment variables:
    - `OPENAI_API_KEY` — your Groq API key (used via OpenAI-compatible endpoint)
    - `NGROK_AUTH_TOKEN` — your ngrok auth token
2. **Run `chatbotG2.py` first.** This starts the backend and prints a public ngrok URL.
3. **Copy the printed backend URL** and paste it into `chatbotUI.ipynb` (set as `BACKEND_URL`).
4. **Run `chatbotUI.ipynb`** to launch the chat interface.

## Sample Outputs

See the `outputs/` folder for screenshots of the assistant answering real analytics questions with charts and follow-up suggestions.
