# Audio Sentiment Analysis with Improved Accuracy

This project explores audio sentiment analysis, aiming to classify audio recordings into different sentiment categories. It demonstrates the effectiveness of using Long Short-Term Memory (LSTM) networks compared to traditional Multi-Layer Perceptrons (MLPs) for this task.

## Motivation

Sentiment analysis of spoken language offers valuable insights in various applications, such as customer service feedback analysis, emotional response detection in media, and sentiment monitoring in social media. However, traditional text-based sentiment analysis methods may not fully capture the nuances of spoken communication. This project addresses this challenge by tackling audio sentiment analysis.

## Approach

The project followed a two-step approach:

**Initial Exploration:**

1. **MLP Model:** A Multi-Layer Perceptron was used as the baseline model.
2. **Feature Extraction:** Relevant features were extracted from audio files to capture sentiment-related attributes.
3. **Evaluation:** The MLP model was trained and evaluated on a dataset of audio recordings.

**Improved Model Implementation:**

1. **LSTM Model:** An LSTM network was adopted due to its ability to learn long-term dependencies in sequential data, which is crucial for audio analysis.
2. **Dataset Enhancement:** A larger and more diverse dataset was acquired or created to improve model generalization and robustness.
3. **Hyperparameter Tuning:** Model hyperparameters were carefully tuned to optimize performance.
4. **Evaluation:** The LSTM model was trained and evaluated on the enhanced dataset.

## Results

The initial MLP model achieved an accuracy of **76.09%**. By implementing an LSTM model with a better dataset, the average accuracy significantly improved to **97.19%**, demonstrating the effectiveness of this approach for audio sentiment analysis.

## Future Work

* Experiment with different deep learning architectures for further accuracy gains.
* Explore techniques for addressing audio noise and speaker variations.
* Integrate the sentiment analysis model into real-world applications.
