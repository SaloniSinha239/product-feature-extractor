# 📱 Product Feature Extractor using FLAN-T5

This project uses a few-shot prompting approach with the *FLAN-T5* model to extract key product features from smartphone reviews. It's designed to demonstrate how generative AI can be used for *text analysis, **feature extraction, and **automated insights* from customer feedback.

---

## 🚀 Project Overview

- *Input*: A list of smartphone reviews (text)
- *Output*: Extracted product features (e.g., battery life, camera quality, overheating)
- *Model*: google/flan-t5-base from Hugging Face
- *Platform*: Google Colab

---

## 🧠 How It Works

1. A few-shot prompt is crafted with examples of reviews and their corresponding features.
2. Each review is passed through the FLAN-T5 model using this prompt.
3. The model returns a list of features mentioned in the review.
4. Results are saved to a CSV file for further analysis or reporting.

---

## 📂 Files

- product_feature_extractor_colab.ipynb: Main Colab notebook
- extracted_features.csv: Output file containing extracted features (generated after running the notebook)

---

## 🛠 Requirements

- Google Colab (no local setup needed)
- Internet connection to access Hugging Face models

---

## 📦 Installation & Usage

1. Open the notebook in Google Colab.
2. Run all cells in order.
3. Upload your own review data or use the sample list provided.
4. Download the extracted_features.csv file from the Colab file browser.

---

## ✨ Example Output

| Review Text                                              | Extracted Features           |
|----------------------------------------------------------|------------------------------|
| The battery lasts all day and the camera is amazing.     | battery life, camera quality |
| The phone heats up quickly during gaming.                | overheating                  |

---

## 📌 Use Cases

- Customer feedback analysis
- Product improvement insights
- Sentiment and feature tagging
- Educational GenAI projects

---

## 📄 License

This project is open-source and free to use for educational and non-commercial purposes.

---

## 🙌 Acknowledgements

- Hugging Face Transformers
- Google FLAN-T5 Model
- IBM watsonx.ai (original project inspiration)
