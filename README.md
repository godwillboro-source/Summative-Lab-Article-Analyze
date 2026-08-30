# ARTICLE ANALYZER
The program below is a text analyser that prompts you for a word to search and get more info about that word in the text provided

# HOW TO RUN
- Clone From https://github.com/godwillboro-source/Summative-Lab-Article-Analyze
- Prepare your text file:
- Place an article.txt file in the same directory as pythonAssessment.py        
- On your terminal, run the python file using python3
- When prompted for a word, input the word
 if the word is not present, the program will throw an error.

# FUNCTIONS
- read_text_file which takes in the parameter of a path containing text, reads it and returns it as a string
- get_words which finds all the words in the text
- count_specific_word which is connected to an input. The function checks how many times the searched word has appeared on the text
- identify_most_common_word which looks through the text string to find the most common word
- calculate_average_word_length which averages the word length in the text
- count_paragraphs which Count paragraphs based on blank line breaks
- protect_abbreviation_periods recognises abbreviations in order for the program to identify between a title and the end of a statement
- count_sentences counts sentences while still ignoring periods inside common abbreviations.
- main which houses the main workings of the cli program


# AI usage
- Building upon existing Python coding foundations, AI was utilized throughout coding as an architectural sounding board and code-review tool