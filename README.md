<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  
</head>
<body>

  <h1>🧠 Natural Language Processing (NLP) Project</h1>

  <p>
    This project delves into the fundamental concepts of Natural Language Processing (NLP), encompassing both Natural Language Understanding (NLU) and Natural Language Generation (NLG). Utilizing Python's NLTK library, the project explores various techniques such as tokenization, stemming, lemmatization, stopword removal, part-of-speech tagging, named entity recognition, and word cloud generation.
  </p>

  <hr>

  <h2>📁 Project Structure</h2>
  <ul>
    <li><strong>NLP_Part1.ipynb</strong> – Jupyter notebook covering NLU concepts.</li>
    <li><strong>POS.png</strong> – Image illustrating part-of-speech tagging.</li>
    <li><strong>POS2.png</strong> – Additional visualization for POS tagging.</li>
    <li><strong>output.png</strong> – Output visualization from the project.</li>
    <li><strong>README.md</strong> – Project documentation.</li>
  </ul>

  <hr>

  <h2>🚀 Getting Started</h2>
  <p>To set up and run the project locally, follow these steps:</p>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/kunalmahadule/Natural-Language-Processing.git</code></pre>
    </li>
    <li>Navigate to the project directory:
      <pre><code>cd Natural-Language-Processing</code></pre>
    </li>
    <li>Install the required Python packages:
      <pre><code>pip install -r requirements.txt</code></pre>
      <em>Note: If a <code>requirements.txt</code> file is not present, ensure that essential packages like <code>nltk</code>, <code>matplotlib</code>, and <code>wordcloud</code> are installed.</em>
    </li>
    <li>Run the Jupyter notebook:
      <pre><code>jupyter notebook NLP_Part1.ipynb</code></pre>
    </li>
  </ol>

  <hr>

  <h2>🧠 Natural Language Understanding (NLU)</h2>
  <ul>
    <li><strong>Tokenization</strong>:
      <ul>
        <li><code>word_tokenize</code> – Splits text into individual words.</li>
        <li><code>sent_tokenize</code> – Splits text into sentences.</li>
        <li><code>blankline_tokenize</code> – Splits text at blank lines.</li>
        <li><code>WhitespaceTokenizer</code> – Tokenizes text based on whitespace.</li>
        <li><code>wordpunct_tokenize</code> – Splits text into alphabetic and non-alphabetic characters.</li>
      </ul>
    </li>
    <li><strong>n-grams</strong>:
      <ul>
        <li><strong>Bigram</strong> – Tokens of two consecutive words.</li>
        <li><strong>Trigram</strong> – Tokens of three consecutive words.</li>
        <li><strong>n-gram</strong> – Tokens of any number of consecutive words.</li>
      </ul>
    </li>
    <li><strong>Stemming</strong>:
      <ul>
        <li><strong>Porter Stemmer</strong> – A widely used stemming algorithm.</li>
        <li><strong>Lancaster Stemmer</strong> – A more aggressive stemming algorithm.</li>
        <li><strong>Snowball Stemmer</strong> – An improved version of the Porter Stemmer supporting multiple languages.</li>
      </ul>
    </li>
    <li><strong>Lemmatization</strong> – Reduces words to their base or dictionary form using WordNet Lemmatizer.</li>
    <li><strong>Stopword Removal</strong> – Eliminates common words that may not contribute meaningful information.</li>
    <li><strong>Part-of-Speech (POS) Tagging</strong> – Assigns grammatical categories (e.g., noun, verb) to each word.</li>
    <li><strong>Named Entity Recognition (NER)</strong> – Identifies and classifies named entities like persons, organizations, and locations.</li>
  </ul>

  <hr>

  <h2>🗣️ Natural Language Generation (NLG)</h2>
  <ul>
    <li><strong>Word Cloud Generation</strong> – Visual representation of word frequency in the text data.</li>
  </ul>

  <hr>

  <h2>🔧 Technologies Used</h2>
  <ul>
    <li>Python</li>
    <li>NLTK (Natural Language Toolkit)</li>
    <li>Matplotlib</li>
    <li>WordCloud</li>
    <li>Jupyter Notebook</li>
  </ul>

  <hr>

  <h2>📄 License</h2>
  <p>
    This project is licensed under the MIT License. See the <code>LICENSE</code> file for details.
  </p>

  <hr>

  <h2>👤 Author</h2>
  <p>
    Developed by <strong>Kunal Mahadule</strong><br>
    GitHub: <a href="https://github.com/kunalmahadule" target="_blank">https://github.com/kunalmahadule</a>
  </p>

  <hr>

  <p>⭐ If you find this project useful, please consider starring the repository!</p>

</body>
</html>
