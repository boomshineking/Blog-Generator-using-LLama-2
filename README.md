This application uses the TinyLlama model, a small and efficient language model inspired by LLaMA 2 architecture.
The model is made available under the TinyLlama project's license (e.g., Apache 2.0 License).
Special thanks to the TinyLlama team for their development work.

TINY LLAMA 🦙 blog generator (https://huggingface.co/spaces/Richard9905/Richards_Blog_generator)

## Project Overview
Imagine being able to generate entire blog articles without relying on external servers or APIs. That's exactly what this project delivers.
Using the powerful **Llama 2 7B GGML** model locally, and crafting a thoughtful prompt template, this application generates full-fledged blog posts—right from your machine.
An interactive **Streamlit** interface ties everything together, making the experience intuitive and accessible.

## Features
- 📄 Custom-designed **Prompt Engineering** to guide blog generation effectively.
- 🖥️ **Offline Inference** with the Llama 2 7B GGML model, ensuring speed and privacy.
- 🚀 A responsive **Streamlit Web Application** for a smooth user experience.
- ⚡ No internet needed during generation — fast, reliable, and completely local.

## Tech Stack
- **Llama 2 7B GGML (offline model)**
- **Python 3.9+**
- **Streamlit for the UI**
- **Prompt Engineering principles**

## How It Works
First, the user inputs a simple topic or keyword inside the Streamlit app.  
Then, behind the scenes, a crafted prompt template reshapes this input into a form that Llama 2 can expand creatively.
The model generates a coherent, detailed blog post in response—sometimes poetic, sometimes sharp—depending on the prompt!
Finally, the text output is displayed immediately on the Streamlit page for review, editing, or use.

## Setup Instructions
> Before starting, ensure the Llama 2 7B GGML model is available locally on your system.

1. Clone the repository:
   ```bash
   https://github.com/boomshineking/llama2-blog-generator
   cd llama2-blog-generator
   ```

2. (Optional but recommended) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows users: venv\Scripts\activate
   ```

3. Install all necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch the Streamlit app:
   ```bash
   streamlit run app.py
   ```

Within seconds, your local blog generator will be live!

## Screenshots
![Screenshot 2025-04-24 224234](https://github.com/user-attachments/assets/636e6dd2-87ab-4939-9bb1-86a64706e7b9)

## Future 
Roadmap
- Introduce selectable blog writing styles (e.g., technical, casual, storytelling).
- Enable automatic saving of generated blogs to local files.
- Improve prompt engineering templates to further boost creativity and coherence.

## License
This repository is provided for educational and personal experimentation purposes.
Commercial usage should adhere to the licensing terms associated with Llama 2.

# 🚀 Let's Connect
Curious about how it all works? Want to collaborate? Feel free to reach out—I'm always up for building something awesome!
