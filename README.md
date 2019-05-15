Jupyter Notebook to generate wordcloud for text that is mix of roman and devnagri scripts. Using WordCloud library of Andreas Muellar. (https://github.com/amueller/word_cloud)

Relevant font file for roman and devnagri scripts can be found in the repo. Any font that supports unicode ranges of roman and devngari can be used to generate the word cloud. 

This notebook generates the wordcloud using a dictionary that contains frequency of each word. (using 'generate_from_dictionary()' function of wordcloud library. 

This python notebook demonstrates generating such dictionary from json, which contians tweets. Has to be suitably modified in case the source is different. 
