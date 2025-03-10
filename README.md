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
<img width="910" alt="Image" src="https://github.com/user-attachments/assets/c9ce2bf5-867e-4d3a-8dfd-15c340f44b01" />


### 2. Recipe Generation
<img width="855" alt="Image" src="https://github.com/user-attachments/assets/17320db6-16cf-4a7e-bda2-69b73f4791e6" />

<img width="892" alt="Image" src="https://github.com/user-attachments/assets/b9f5e9de-9fef-4098-bd56-26dba4311c7f" />

### 3. Image Generation

<img width="852" alt="Image" src="https://github.com/user-attachments/assets/96e80d7e-15bb-4cf5-861b-dc6c9ca60d59" />

### 4. Conversational Chat

<img width="1283" alt="Image" src="https://github.com/user-attachments/assets/1efc3df5-9346-4e79-8992-f7adfbc02d95" />

<img width="859" alt="Image" src="https://github.com/user-attachments/assets/3376d445-1d81-42b2-9eed-e2d3686bb957" />

<sup>_Create an `images` folder in your repository and place actual screenshots there. Update these file paths accordingly._</sup>

<br />

