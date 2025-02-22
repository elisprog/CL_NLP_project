# CL_NLP_project
A midterm project for 'Computational linguistics' program in HSE
'Analysis of BBC Mundo News Spanish lexis for teaching purposes'

Interactive presentation
https://view.genially.com/67b8d17fc1dc50bb869a581b/presentation-clnlpproject

Includes Python code:

1. scraping and parsing of BBC Mundo News website
   (request.get(), BeautifulSoup, regular expressions)
[8 sections of the BBC Mundo News website: amlat_section.txt, cienc_section.txt, cult_section.txt, econ_section.txt, festiv_section.txt, intern_section.txt, salud_section.txt, tecnolog_section.txt]
3. scraping and parsing of Instituto Cervantes Lexical contents for students of SSL (Spanish as a second language) [all_words_cervantes.txt (both specific and general terms), words_cervantes.txt (specific terms), words_gen_cervantes.txt (general terms)]
4. preprocessing of text corpus
   (NLTK, stopwords) [some preprocessed text files couldn't have been uploaded to GitHub technically]
5. unigram and bigram selection of all corpus with special attention to economy articles of the corpus (FreqDist, BigramFinder, Likelihood, Student´s t-distribution, POS part of speech with Stanza)

6. TF-IDF key words and most frequent words in economy articles of the corpus
 
7. comparison of the percentage of lexical contents of Instituo Cervantes website in all corpus with special attention to economy articles of the corpus

 ![freq_all_corp](https://github.com/user-attachments/assets/23e72eb7-1691-4869-9e2b-c26b2c11fe94)
  ![tf_idf_econ_words](https://github.com/user-attachments/assets/6a230a03-d72e-4dc7-bfa9-0cce46d779a8)
   ![uniq_econ_freq_wordcloud](https://github.com/user-attachments/assets/0bab7951-f764-4cfe-8f2d-399cd0a91c71)
