Natural Language Processing  
Next Word Prediction using Language Model 
Your task is to develop an app for next word prediction using Language Model.  
• Given a text corpus with vocabulary. V , 
• Given a sequence of words, x(1),x(2),…,x(t) , 
• A language model essentially computes the probability distribution of the next word.x(t+1) . 
A language model, thus, assigns a probability to a piece of text. 
How do we compute these probabilities? 
To compute the probabilities of these n-grams and n-1 grams, we just go ahead and  start counting them in a large text corpus! 
Minimum Requirements: 
The next word prediction game should let the user write the first word and then the next  word should be suggested by the program. You can give the option of using space or  enter key to choose the suggested word. User should be able to select a word from 3 top words in the list. 
The game should also provide a menu to select the value of N which can be 1,2 or 3 where  N is used to calculate N-grams. Precisely the game should be played using unigram,  bigram and trigram language model. 
The drawback of language modeling is sparseness so to address it provide another option  of choosing smoothness technique. The following options for smoothing should be  available. 
• Backoff 
• Interpolation 
• Good Turing 
• Kneser-Ney 
Play the game with all the combinations from the options (unigram, bigram trigram with  and without smoothing) and analyze.  

