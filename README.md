# Jane_Austen_Text_Generator

Create a character RNN to generate text. The RNN is trained on Jane Austen novels (Pride and Prejudice, Sense and Sensibility, Persuasion, and Emma). The book .txt files are downloaded from Project Gutenberg and processed in the Prepare_corpus notebook. A training and validation/test corpus are created and the .txt files are available in the repository. A tokenizer is trained on the corpus and is pickled for later use in training and text generation. 

The Char_RNN notebook loads the .txt files and the tokenizer from Google Drive and trains an RNN with GRU cells. I am still training the model, but the most current version is saved as a keras model in the Checkpoint. The notebook loads the most recently saved checkpoint model from Drive and begins training the model again. 
