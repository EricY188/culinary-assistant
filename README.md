# culinary-assistant
use streamlit and gpt API to create a personal culinary-assistant
# Culinary Assistant

A simple Streamlit application that uses OpenAI's APIs for:
- Generating Chinese recipes (using single-shot or few-shot prompts).
- Creating images via OpenAI’s Image (DALL·E) endpoint.
- Conversational chat with memory, thanks to `st.session_state`.

## Features

1. **Recipe Generation**  
   - **Single-shot Prompt**: Quick recipe suggestions without examples.  
   - **Few-shot Prompt**: More detailed, context-rich recipes with provided examples.

2. **Image Generation**  
   - Generates images based on a text prompt using DALL·E.  

3. **Conversational Chat**  
   - Retains conversational context in `st.session_state` so the user can have a back-and-forth conversation without losing previous context.

## Installation

1. Clone or download the repository to your local machine.
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
