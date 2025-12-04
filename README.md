# 🎵 Lab 1: Playlist Chaos

Your "AI Pair Programmer" built a music sorting app. It looks great, but it logic is...chaotic. Songs disappear, everything gets sorted as "Hype", and the "Lucky" button crashes the app.

**Your Mission:** Use an AI chatbot to investigate the bugs, explain *why* they are happening, and fix the code.

## 🛠️ Setup

1. **Install the requirement:**

    ```bash
    pip install -r requirements.txt
    ```

2. **Run the app:**

    ```bash
    streamlit run app.py
    ```

## 🕵️‍♀️ Your Tasks

1. **The "Hype" Bug:** Add a quiet song like "Sleepy Lullaby". Notice it gets sorted into **Hype**. Ask your AI: *"Why does this Python condition `if "rock" or "punk" in title` always evaluate to True?"*
2. **The "Ghost" Bug:** Add a song. Then add another. Notice the first one disappears? Ask your AI: *"How do I persist variables in Streamlit so they don't reset on every button click?"*
3. **The "Crash" Bug:** Click the "I'm Feeling Lucky" button while the list is empty. Watch the app crash. Use AI to write a **guardrail** to prevent this.
