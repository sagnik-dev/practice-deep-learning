# Practice Deep Learning

Hands-on deep learning labs and experiments implemented primarily in Jupyter
notebooks. The repository progresses from basic perceptrons and gradient
descent to convolutional, recurrent, and text-classification models.

## Topics covered

- Perceptron learning for logic gates
- Manual forward and backward propagation
- Multilayer perceptron implementation for XOR
- Binary classification with logistic regression
- California housing regression
- MNIST classification with dense and convolutional neural networks
- Recurrent neural network fundamentals
- Email spam classification with a bag-of-words representation

## Repository contents

| Notebook | Focus |
| --- | --- |
| `1st lab.ipynb`, `2rd.ipynb` | Perceptron training and logic gates |
| `dl_3.ipynb` | Sigmoid activation and gradient descent |
| `Multilayer Perceptron for XOR(dl-5) .ipynb` | XOR with a hand-built multilayer network |
| `dl_6.ipynb` | California housing regression |
| `dl_7.ipynb` | Dense neural networks for MNIST |
| `Lab 8.ipynb` | CNN architecture comparisons for MNIST |
| `dl_9.ipynb` | RNN calculations and sequence classification |
| `email_classification_(lab_4)_.ipynb` | Email spam classification |

## Getting started

1. Install Python 3.9 or newer.
2. Install Jupyter and the libraries used by the notebooks:

   ```bash
   python -m pip install jupyter numpy pandas matplotlib scikit-learn tensorflow
   ```

3. Start Jupyter from the repository root:

   ```bash
   jupyter notebook
   ```

4. Open a notebook and run its cells from top to bottom.

Some notebooks download datasets through Keras or scikit-learn. The email
classification notebook expects a `spam_or_not_spam.csv` file and was written
for Google Colab; update its upload or file path cells when running locally.

## Notes

These notebooks are learning exercises and may use different model
configurations, preprocessing steps, and training settings. Re-running cells
can produce different results when random initialization is used.
