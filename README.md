

# H2H - Hate Detector  

H2H is an advanced hate detection system designed to identify and flag harmful content in tweets. It predicts whether a tweet contains toxic, severe toxic, obscene, threat, insult, or identity hate content, promoting healthier online interactions and fostering a safer social media environment.

---

## **Installation**

To set up H2H on your local machine, follow these steps:

1. **Install Dependencies**  
   Ensure you have Python and Jupyter Notebook installed on your machine. You can download them from [Python.org](https://www.python.org/) and [Jupyter](https://jupyter.org/).

2. **Download the Dataset**  
   The project uses the Jigsaw Toxic Comment Classification Challenge dataset from Kaggle. Download it [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data).

3. **Clone the Repository**  
   Clone this repository or download it as a ZIP file and extract it.  
   ```bash
   git clone https://github.com/GLYSATVIK/H2H.git
   cd H2H
   ```

4. **Launch the Notebook**  
   Open the `code.ipynb` notebook in Jupyter Notebook. Follow the instructions provided to train the model and make predictions.

---

## **Usage**

H2H allows you to analyze tweets for hate content.  
1. Train the model using the instructions in `code.ipynb`.  
2. Input the text of the tweet into the model.  
3. The system will output whether the tweet contains any of the following:  
   - Toxic  
   - Severe Toxic  
   - Obscene  
   - Threat  
   - Insult  
   - Identity Hate  

### Example Output  
```plaintext
WELCOME TO HATE DETECTOR: H2H  
1/1 ━━━━━━━━━━━━━━━━━━━━ 0s 106ms/step  
tweet: "I'll kill you"  
toxic: True  
severe_toxic: False  
obscene: False  
threat: False  
insult: False  
identity_hate: False  
```

---

## **Dataset**

The system is trained on the **Jigsaw Toxic Comment Classification Challenge dataset**.  
- **Source:** [Kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data)  
- The dataset contains labeled comments from Wikipedia discussions, annotated with different types of toxicity.

---

## **Model Performance**

| Model Version | Accuracy | Precision | Layers in Neural Network |
|---------------|----------|-----------|--------------------------|
| **Model 1** (`code.py`) | 93.75%   | 50%       | 7                        |
| **Model 2** (`codev2.py`) | 98.95%   | 75%       | 11                       |

- **Future Improvements:**  
   Adjusting the neural network architecture and hyperparameters can further enhance accuracy and precision.

---

## **Contents**

- `code.py`  
   - Version 1 of the model.  

- `codev2.py`  
   - Version 2 of the model with improved architecture and performance.  

- `output.txt`  
   - Sample outputs for testing.

---

## **Contributing**

Contributions are always welcome! To contribute:  
1. Fork the repository.  
2. Make your changes.  
3. Submit a pull request with a detailed description of your enhancements.  

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

