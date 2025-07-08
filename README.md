# 🇻🇳 Vietnamese Luc Bat Poetry Generation using GPT-2 and Transformer

This project aims to generate Vietnamese **Luc Bat** poems (thơ lục bát) using a fine-tuned **GPT-2 model** with custom training data and structural constraints.

## 📜 Luc Bat Poetry
Luc Bat is a traditional Vietnamese form of poetry consisting of alternating 6-syllable and 8-syllable lines, with strict rhyming and tone rules. Generating this form requires both **syntactic fluency** and **rhythmic precision**.

## 🚀 Project Goals
- Build a dataset of Vietnamese Luc Bat poems.
- Fine-tune a GPT-2 model (via HuggingFace Transformers) on this structured poetic data.
- Generate poems that respect the Luc Bat form in rhythm and rhyme.
- Provide evaluation and examples of generated poetry.

## 🛠 Technologies Used
- Python
- HuggingFace Transformers
- PyTorch
- Google Colab / Jupyter Notebook
- GitHub Projects (for task tracking)


## 📈 Model Training
- Base model: `GPT-2 small` (124M)
- Tokenizer: Byte-level BPE tokenizer (customized if needed)
- Training steps: 2–5 epochs with early stopping
- Loss function: Causal LM Loss
- Evaluation: Manual + metric-based rhyme/structure checking

## 🧪 Sample Output
> Trăng mờ rơi xuống hàng tre  
> Đêm nay em nhớ lời thề năm xưa  
> Gió về thổi nhẹ như mưa  
> Hồn ai lạc giữa trời thưa lạnh lùng...

## 🗂 Dataset
- Custom collected from public Vietnamese poetry websites and sources.
- Preprocessed to enforce correct Luc Bat formatting.

## ✅ To-Do
- [x] Data collection & preprocessing  
- [x] GPT-2 fine-tuning  
- [x] Evaluation & manual checking  
- [ ] Deploy demo web/app interface (optional)

## 🤝 Contributors
- **Nguyen Minh Chau** – Prompt engineering, model fine-tuning, evaluation
