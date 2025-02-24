# Next Word Prediction Model using a Transformer based Architecture🚀 
<!DOCTYPE html>
<html lang="en">
<body>  
  <h2>📄 Description</h2>
  <p>
    This project implements a next word prediction model using a transformer-based architecture built with TensorFlow. Trained on the <a href="./data/Oxford_English_Text.txt">Oxford English Text</a> dataset, the model generates contextually relevant word predictions for a given input. It showcases advanced NLP techniques for sequence modeling and text generation.
  </p>
  
  <h2>✨ Interesting Techniques</h2>
  <ul>
    <li>🔍 <strong>Transformer Architecture:</strong> Utilizes self-attention and positional encoding for contextual learning.</li>
    <li>📝 <strong>Text Preprocessing:</strong> Cleans and tokenizes raw text data using regular expressions. Learn more about <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_Expressions" target="_blank">Regular Expressions</a> on MDN.</li>
    <li>⚙️ <strong>Sequence Modeling:</strong> Trains the model to predict subsequent words based on learned language patterns.</li>
  </ul>
  
  <h2>🔧 Technologies & Libraries</h2>
  <ul>
    <li>🐍 <strong>Python:</strong> Core programming language for model development.</li>
    <li>🤖 <strong>TensorFlow & Keras:</strong> Frameworks used for building and training the transformer model.</li>
    <li>📚 <strong>NumPy:</strong> For efficient numerical computations.</li>
    <li>🔤 <strong>NLTK (or similar):</strong> For text tokenization and preprocessing.</li>
  </ul>
  
  <h2>📁 Project Structure</h2>
  <pre>
/notebooks
   Next_word_predictor_Final.ipynb   # Jupyter Notebook with the full model code and training process
/data
    Oxford English Text.txt           # Dataset text file for training the model
/models
    (model checkpoints & saved weights)   # Stores trained model artifacts
/results
    (evaluation metrics & plots)      # Contains output files like accuracy graphs and logs
/utils
    (helper scripts)                  # Utility functions for data processing and visualization
  </pre>
  <p>
    <strong>/notebooks:</strong> Main development environment with the Jupyter Notebook.<br>
    <strong>/data:</strong> Contains the text dataset used for training.<br>
    <strong>/models:</strong> Houses saved checkpoints and model weights after training.<br>
    <strong>/results:</strong> Includes evaluation outputs and performance plots.<br>
    <strong>/utils:</strong> Utility scripts for text preprocessing and other helper functions.
  </p>
</body>
</html>
