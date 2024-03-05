# Language Detection using Character Trigrams and LID

## Project Overview
This project presents a state-of-the-art Language Identification (LID) model capable of classifying text samples into one of six languages (English, Spanish, Italian, Dutch, German, and French) with exceptional accuracy. By leveraging character trigrams and the Lidstone Law for probability calculation, our model achieves a remarkable F1-score of 99.89%, demonstrating its efficacy and precision in language detection.

## Features
- **High Accuracy**: Achieves an F1-score of over 99.89%, showcasing the model's ability to accurately predict the language of given text samples.
- **Character Trigrams**: Utilizes trigrams of characters as the fundamental feature for language identification, ensuring robust and nuanced language differentiation.
- **Lidstone Law (LID)**: Employs the Lidstone Law for smoothing and probability estimation, enhancing the model's predictive capability across diverse linguistic patterns.

## How to Execute
1. Ensure `main.py` is in the same directory as `abia_bicing.py` for access to `Estacion` and `Estaciones` classes.
2. Experiment function calls are commented out from line 70 in `main.py`. Uncomment the desired experiment (e.g., `experimentoX()`) for execution.
3. The experiment 5 must be executed twice for each heuristic. Adjust the `coste_transporte` parameter in `parameters_bicing.py` to `False` (Heuristic 1) or `True` (Heuristic 2) accordingly.

## Visualizations and Analysis
- The project includes a detailed analysis of classification errors, emphasizing the model's strengths and areas for improvement.
- Pygame is used for route visualization, and custom `__repr__()/__str__()` methods provide insights into the initial and solved states.

## Conclusion
With an F1-score exceeding 99.89%, our language detection model sets a new benchmark for accuracy and efficiency in the field. Its success lies not just in its sophisticated algorithmic foundation but also in its potential for real-world application across various sectors requiring rapid and precise language identification.

