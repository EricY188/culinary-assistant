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
   pip install streamlit openai
# Culinary Assistant

A simple Streamlit application that uses OpenAI's APIs to:
- Generate Chinese recipes (with **Single-shot** or **Few-shot** prompts)
- Create dish images via [DALL·E](https://openai.com/product/dall-e-2/)
- Provide a conversational chat interface that preserves context in `st.session_state`

<br />

## Table of Contents

- [Features Overview](#features-overview)
- [Demo / Screenshots](#demo--screenshots)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [OpenAI API Key Configuration](#openai-api-key-configuration)
- [How It Works](#how-it-works)
  - [Single-shot vs Few-shot Prompts](#single-shot-vs-few-shot-prompts)
  - [Chat with Memory](#chat-with-memory)
  - [Text-to-Image Generation](#text-to-image-generation)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

<br />

## Features Overview

1. **Recipe Generation**  
   - **Single-shot Prompt**: Generates a quick recipe without multiple examples.  
   - **Few-shot Prompt**: Provides detailed, example-based recipes.

2. **Image Generation**  
   - Generates images of your dish idea using OpenAI’s DALL·E endpoint.  

3. **Conversational Chat**  
   - Retains conversation history and context in `st.session_state`, allowing for a natural, ongoing conversation.  

<br />

## Demo / Screenshots

Here are some placeholder images to illustrate the UI. Replace them with your actual screenshots once you have them:

### 1. Main Page
![Main UI](./images/main_ui_example.png "Main UI screenshot")![Uploading Screenshot 2025-03-09 at 10.45.23 PM.png…]()


### 2. Recipe Generation
![Recipe Generation](./images/recipe_generation_example.png "Recipe Generation screenshot")

### 3. Image Generation
![Image Generation](./images/image_generation_example.png "Image Generation screenshot")

### 4. Conversational Chat
![Chat Interface](./images/chat_interface_example.png "Chat Interface screenshot")

<sup>_Create an `images` folder in your repository and place actual screenshots there. Update these file paths accordingly._</sup>

<br />

## Project Structure

Below is a minimal overview of the repository contents:
