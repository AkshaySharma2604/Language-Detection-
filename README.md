Language Detection Model
🔍 Overview
This project uses a Multinomial Naive Bayes classifier to detect the language of a given text. The model is trained on a dataset containing 22 languages, with 1000 samples per language. It achieves an accuracy of ~95.3% on the test set.

📂 Dataset

The dataset includes text samples in the following languages:

Estonian, Swedish, English, Russian, Romanian, Persian, Pushto, Spanish, Hindi, Korean, Chinese, French, Portugese, Indonesian, Urdu, Latin, Turkish, Japanese, Dutch, Tamil, Thai, Arabic.

🛠️ Dependencies

Python 3.x
Libraries:
bash
pip install pandas scikit-learn requests numpy
🚀 How to Use

Clone the repository:
bash
git clone https://github.com/yourusername/language-detection.git
cd language-detection
Run the script:
bash
python language_detection.py
Enter text when prompted:
plaintext
Enter a Text: வணக்கம் என் பெயர் அக்ஷய் ஷர்மா
['Tamil']

What Happens If the Model Doesn’t Recognize the Language?

If the input text is empty, it prints:
plaintext
empty string
If the text is in a language not in the training data (e.g., Greek, Hebrew, etc.), the model will still predict one of the 22 supported languages, but the result may be incorrect.
