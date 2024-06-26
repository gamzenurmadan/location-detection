The model i used is the fine-tuned version of [Babelscape/wikineural-multilingual-ner](https://huggingface.co/Babelscape/wikineural-multilingual-ner). 
I fine-tuned the model with Turkish [wikiann dataset](https://huggingface.co/datasets/unimelb-nlp/wikiann).
You can reach the model [here](https://huggingface.co/gamzenurmadan/expanded-multilingual-ner).
In this notebook I wrote a code that takes a sentence, detects the location, and returns the coordinates.
