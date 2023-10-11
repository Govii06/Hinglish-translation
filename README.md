# Hinglish-translation

I already took the available model, which is capable of translating a given text in some given language X to some text in language Y. The Language Technology Research Group at the University of Helsinki has brought 1300+ Machine translation(MT) models readily available on the HuggingFace platform.
Helsinki-NLP/opus-mt is common in all models. Just the rest of the part differs in all. That means all model names have the following format: Helsinki-NLP/opus-mt-{src}-{tgt}, where src and tgt placeholders contain the language codes. So, for English to Hindi text translation, the model name should be Helsinki-NLP/opus-mt-en-hi.
This model is trained on OPUS dataset. This open parallel is the collection of translated texts from the web. It also includes translations of Wikipedia, Wikisource, Wikibooks, Wikinews, and WikiQuote web pages. 
And the required pre-processing step also includes tokenizing text using the SentencePiece library.

Steps to run:
Download the given py file and upload it in Jupyter or google colab.

Run step by step and then you will get the output.

You can give any English words or sentences to convert to hindi aka hinglish. 
