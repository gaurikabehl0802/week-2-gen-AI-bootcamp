# Multi-Prompt Transform Application

A lightweight Web UI built with Python, Gradio, and the Google GenAI SDK. This application allows users to experience firsthand how system-level prompt styling adapts a single base AI model (`gemini-2.5-flash`) into distinct functional tools.

## Features
- **User Key Security:** Requires users to supply their own Google AI Studio API key.
- **Robust Error Handling:** Validates empty inputs and intercepts bad API requests gracefully.
- **3 Prompting Dimensions:** - *ELI5 Mode:* Converts dense topics into child-friendly analogies.
  - *Professional Mode:* Elevates slang/casual thoughts into corporate-ready prose.
  - *Quiz Mode:* Parses inputs into a dynamic multiple-choice testing layout.

## How to Run Locally
1. Clone the repository.
2. Install dependencies: `pip install google-genai gradio`
3. Run `python app.py`
4. public url:  https://8b7fd0801e44290c8b.gradio.live
5. generate gemini api key: https://aistudio.google.com/api-keys?project=gen-lang-client-0090723066
