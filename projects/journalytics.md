[About](../index.md) | [Portfolio](../portfolio.md) | [Skills](../skills.md) | [Contact](../contact.md)

# Journalytics

## Overview
**Journalytics** is a cutting-edge journaling platform designed to help users document their thoughts and emotions while gaining deeper insights through advanced sentiment analysis.

## How Sentiment Analysis Works
Journalytics uses a sophisticated machine learning model based on the pretrained **BERT (Bidirectional Encoder Representations from Transformers)** architecture. Each journal entry is analyzed across six primary emotional dimensions:
- Sadness
- Joy
- Love
- Anger
- Fear
- Surprise

### Behind the Scenes
1. **Data Preparation**:
   - Journal entries are vectorized using BERT embeddings to capture their semantic and emotional meaning.
   - A unique data augmentation technique combines these embeddings to generate nuanced emotional representations.

2. **The Model**:
   - A fully connected neural network processes the embeddings to assign weights (0–1) for each emotional category.
   - Dropout regularization ensures robustness, while a sigmoid activation outputs normalized intensities.

3. **Output**:
   - The system provides a vector of emotional intensities, representing the relative presence of each emotion in the text.

## Applications of Emotional Insights
- **Mood Tracking**: Monitor emotional trends over time to identify patterns.
- **Mental Health Awareness**: Reflect on triggers and emotional fluctuations in journal entries.
- **Progress Visualization**: Quantify emotional states and track improvements.

## Technologies Used
- **Languages**: Python
- **Libraries and Frameworks**:
  - Transformers (Hugging Face), PyTorch, NumPy, Pandas, Matplotlib, Seaborn
- **Architecture**: Pretrained BERT for embeddings, fine-tuned with a custom feedforward neural network.

## Future Enhancements
- Expand language support for multilingual sentiment analysis.
- Introduce advanced emotion categories (e.g., gratitude, envy).
- Build a web-based user interface for real-time journal analysis.

## Repository
Explore the source code and detailed implementation:
[GitHub Repository](https://github.com/William040802/Journalytics)

[Back to Portfolio](../portfolio.md)
