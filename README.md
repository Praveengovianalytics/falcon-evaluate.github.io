# 📚 Falcon Evaluate - Evaluation Metrics Guide

---

## 1. 📖 Readability and Complexity

### 📘 ARI (Automated Readability Index)
- **Description**: A readability formula that gauges the understandability of English text. It considers characters per word and words per sentence. A higher ARI indicates text that is harder to read.
  
  **Example**: For a sentence like "The cat sat on the mat.", the ARI might be relatively low, indicating easy readability.

### 📙 Flesch-Kincaid Grade Level
- **Description**: Estimates the grade level a person must have reached to understand the text. The formula considers the sentence length and the number of syllables per word.
  
  **Example**: A passage from a children's book might have a Flesch-Kincaid Grade Level of around 3, indicating it's suitable for third graders.

---

## 2. 🧠 Language Modeling Performance

### 💡 Perplexity
- **Description**: Quantifies how well a probability distribution predicts a sample. In NLP, it represents how well a language model predicts a piece of text. A lower perplexity indicates better predictive performance.
  
  **Example**: If a model predicts the next word in the sentence "The sky is ___" as "blue" with high certainty, it would have low perplexity.

---

## 3. ⚠️ Text Toxicity

### ☣️ Toxicity Level
- **Description**: Represents the degree of harmful or inappropriate content in a text. A higher value indicates a higher likelihood of the text being toxic.
  
  **Example**: For the phrase "I hate you", a model might assign a higher toxicity level compared to "I love ice cream".

---

## 4. 🧲 Text Similarity and Relevance

### 🌐 BLEU (Bilingual Evaluation Understudy) Score
- **Description**: Evaluates the similarity between machine-generated text and human-generated reference text, commonly used in machine translation.
  
  **Example**: Translating "Bonjour" to "Hello" in English might yield a high BLEU score.

### 📏 Cosine Similarity
- **Description**: Measures the cosine of the angle between two non-zero vectors, determining the similarity between two pieces of text.
  
  **Example**: The phrases "cat" and "kitten" might have a high cosine similarity because they're both related to felines.

### 🤝 Semantic Similarity
- **Description**: Measures the likeness of meaning or semantics between two pieces of text.
  
  **Example**: "Sofa" and "couch" would have high semantic similarity as they refer to the same piece of furniture.

### ✂️ Jaccard Similarity
- **Description**: Compares the similarity and diversity of sample sets. It's the size of the intersection divided by the size of the union of two sets.
  
  **Example**: For sets {A, B} and {B, C}, the Jaccard similarity is 1/3 or 0.33.

---

## 5. 🕵️ Information Retrieval

### 🎯 Precision
- **Description**: Represents the fraction of relevant instances among the retrieved instances. A measure of exactness.
  
  **Example**: If a search yields 5 relevant results out of 10, the precision is 0.5.

### 📌 Recall
- **Description**: Represents the fraction of relevant instances that were retrieved over the total amount of relevant instances. A measure of completeness.
  
  **Example**: If there are 5 relevant results in the entire dataset and a search retrieves 4 of them, the recall is 0.8.

### ⚖️ F1-Score
- **Description**: The harmonic mean of precision and recall. It provides a balance between the two when their values diverge.
  
  **Example**: Given a precision of 0.5 and a recall of 0.8, the F1-Score would be approximately 0.63.

