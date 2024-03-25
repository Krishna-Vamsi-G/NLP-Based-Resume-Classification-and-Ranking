
<body>
    <h1>NLP-based Resume Classification and Ranking System</h1>
    <h2>Overview</h2>
    <p>This system leverages Natural Language Processing (NLP) and Machine Learning (ML) techniques to automate the screening of resumes, facilitating the recruitment process. It aims to classify resumes into various job categories and rank them according to their relevance to specific job descriptions. This not only streamlines the hiring process but also enhances the quality of hiring decisions by ensuring a fair and objective evaluation of candidates.</p>
    
  <h2>Features</h2>
    <ul>
        <li><strong>Automated Classification:</strong> Utilizes NLP techniques to classify resumes into different categories based on their content.</li>
        <li><strong>Intelligent Ranking:</strong> Ranks resumes based on their suitability and relevance to the job description, using advanced text similarity metrics.</li>
        <li><strong>Bias Reduction:</strong> Aims to reduce hiring bias by providing an objective basis for resume evaluation.</li>
        <li><strong>Efficiency Improvement:</strong> Significantly decreases the time and resources required for manual resume review.</li>
    </ul>
    
  <h2>Technologies Used</h2>
    <p>Python: Primary programming language.<br>
    Libraries: Pandas, Scikit-learn, Spacy, NLTK, Gensim, Matplotlib, Seaborn, Wordcloud, Textdistance, Textract.<br>
    Techniques: Tokenization, Stop-word Removal, Lemmatization, TF-IDF Vectorization, Various ML Classification and Ranking Models.</p>
    
  <h2>Installation</h2>
    <p>To run this system, ensure you have Python installed on your machine and then follow these steps:</p>
    <ol>
        <li>Clone this repository.</li>
        <li>Navigate to the project directory and install the required Python packages:<br><code>pip install -r requirements.txt</code></li>
    </ol>
    
  <h2>Usage</h2>
    <ol>
        <li>Prepare your dataset according to the guidelines provided in the dataset section.</li>
        <li>To start the resume classification and ranking process, run:<br><code>python app.py</code></li>
        <li>Follow the on-screen instructions to input job descriptions and get ranked resumes.</li>
    </ol>
    
  <h2>Dataset</h2>
    <p>The system is trained on a Kaggle dataset comprising 2208 resumes in .pdf and .docx formats. The dataset is preprocessed to remove unnecessary information, and resumes are classified into distinct categories before being ranked according to job descriptions.</p>
    
  <h2>How It Works</h2>
    <ul>
        <li><strong>Preprocessing:</strong> Cleans and prepares resume data using NLP techniques.</li>
        <li><strong>Classification:</strong> Employs ML models (e.g., Naive Bayes, Random Forest, SVC) to categorize resumes.</li>
        <li><strong>Ranking:</strong> Utilizes text similarity metrics (e.g., Cosine Similarity, Jaccard Similarity) to rank resumes based on job descriptions.</li>
    </ul>
    
  <h2>Contributing</h2>
    <p>Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.</p>
    

<h2>Acknowledgements</h2>
<p>Developed by Krishna Vamsi G and Sriram K at the University of Central Florida.</p>

<h2>References</h2>
<p>For a detailed understanding of the methodologies and technologies used in this project, refer to the Project Report.</p>
</body>
</html>
