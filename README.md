# 🦅 FalconChat: Multi-Turn Conversational AI with Falcon-7B-Instruct

FalconChat is a real-time, interactive chatbot built using the **Falcon-7B-Instruct** model via **HuggingFace Transformers**. The chatbot enables natural, multi-turn conversations through dynamic prompting and response generation. It leverages **PyTorch**, **transformers pipeline**, and **token-based control** to simulate engaging dialogues between two characters.

## ✨ Features

- 💬 Multi-turn dialogue simulation  
- ⚙️ Real-time response generation with `text-generation` pipeline  
- 🧠 Based on **tiiuae/falcon-7b-instruct** model  
- ⚡ Auto device mapping using `torch` for efficient execution  
- 🧩 Custom character naming and dialogue tracking  

## 🛠️ Tech Stack

- **Model**: [Falcon-7B-Instruct](https://huggingface.co/tiiuae/falcon-7b-instruct)  
- **Libraries**: `transformers`, `torch`  
- **Language**: Python  
- **Tokenizer Control**: EOS & newline token logic for natural stopping  

## 🧰 Requirements

- **Python** ≥ 3.7  
- **GPU** with ≥ 12 GB VRAM recommended (for `bfloat16` precision)

## 🚧 Limitations & Future Work
- 🚫 Heavy memory usage: Falcon-7B-Instruct is a large model, limited support on CPUs or lower-end GPUs.
- 🔄 No saving of conversations or UI interface. Build UI/UX with Streamlit or Gradio frontend.
