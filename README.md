# Text-Summarization

Text summarization is the task of shortening long pieces of text into a concise summary that preserves key information, content and overall meaning of the text. This project uses HuggingFace Transformers, which offer pretrained Transformers, for performing easy text summarization. Summarization is usually done using an encoder-decoder model, such as Bart or T5. We have used both in this project.

## Files:
Text Summarization.py: the python code is contained in this file
webpage.txt: contains HTML script of the webpage we want to summarize.
article.txt: contains the text from a webpage after BeautifulSoup library has parsed it and turned it more readable
summaryBART.txt : contains the output of the summarization using BART model
summaryT5.txt: contains the output of the summarization using T5 model


## Installations:
This project requires Python 3.x and the following Python libraries installed:

BeautifulSoup
transformers
urllib (in-built)
