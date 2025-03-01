These tasks cover a range of NLP techniques, from basic visualization to advanced feature extraction. 

1. **Commentary Word Cloud**  
   - Load the commentary dataset.  
   - Clean text (remove stop words, punctuation, and unnecessary whitespace).  
   - Use `WordCloud` from `wordcloud` library to generate the figure.  

2. **Commentary to Table (Regex Extraction)**  
   - Identify patterns for extracting bowler, batter, ball type, shot type, speed, and runs.  
   - Use Python’s `re` module for pattern matching.  
   - Store extracted data in a structured format (like a Pandas DataFrame).  
   - (Your expected output mentions a line chart related to cell phones—did you mean a table instead?)  

3. **Text Pre-processing with Scikit-learn**  
   - Implement `CountVectorizer()` and `TfidfVectorizer()` from `sklearn.feature_extraction.text`.  
   - Convert commentary into numerical representations.  
   - Compare the generated vectors to understand differences between bag-of-words and TF-IDF.  

4. **TF-IDF from Scratch**  
   - Calculate Term Frequency (TF) and Inverse Document Frequency (IDF) using their respective formulas.  
   - Implement the formula manually in Python.  
   - Compare results with `TfidfVectorizer` from scikit-learn.  

