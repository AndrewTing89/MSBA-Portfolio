# 🌐 English-to-Spanish Machine Translation with Pre-trained Transformers

This project showcases a practical application of **Natural Language Processing (NLP)** using pre-trained transformer models from the Hugging Face library. The task involves translating English sentences to Spanish and evaluating the model's performance on various sentence types.

---

## 🧠 Project Highlights

- **Model Used:** `Helsinki-NLP/opus-mt-en-es` — a top-performing pre-trained model for English-Spanish translation.
- **Frameworks & Tools:** Hugging Face Transformers, PyTorch, Google Colab
- **Functions Built:**
  - `translate_to_spanish(sentence)` for single input
  - Batch translation handler using tokenizer padding/truncation
- **Evaluation Metrics:** BLEU score computed to assess translation accuracy

---

## 🔧 Implementation Overview

- **Model Setup:** Loaded the pre-trained model and tokenizer from Hugging Face.
- **Translation Pipeline:** Implemented a tokenizer-integrated function for translating sentences.
- **Batch Processing:** Extended logic to handle a list of sentences using attention to input size compatibility.
- **Sample Translations:** Demonstrated the pipeline on three example sentences.

---

## 📊 Evaluation

- **Test Dataset:** Custom dataset of 10 diverse English sentences (simple, compound, idiomatic).
- **BLEU Score:** Calculated to quantify translation quality.
- **Qualitative Analysis:**
  - ✅ Strong performance on simple and moderately complex sentences
  - ⚠️ Some inaccuracies in idiomatic translations
  - ✍️ Suggested improvements include fine-tuning or post-processing for idioms

---

## 💡 Key Takeaways

### ✅ Advantages of Pre-trained Models:
- Rapid prototyping without intensive training
- State-of-the-art performance on common language pairs
- Easy integration with Hugging Face pipelines

### ⚠️ Limitations:
- Struggles with domain-specific jargon and idiomatic expressions
- Potential for grammatical correctness without full semantic accuracy

### 🔁 Improvement Suggestions:
- Fine-tune the model on a specific dataset (e.g., financial, legal, healthcare)
- Apply rule-based post-processing for cultural or idiomatic corrections

---

## 📂 Files

- `BAX_452 - HW6 - Q1.html`: Full notebook code and results (HTML export)
- `README.md`: This file

---

## 👨‍💻 About the Author

**Andrew Ting**  
Master of Science in Business Analytics  
UC Davis, Class of 2025  
*Aspiring Data Scientist with interests in NLP, Computer Vision, and AI-driven insights*
