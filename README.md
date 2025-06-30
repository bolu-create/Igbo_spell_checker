This project is a context-sensitive spell corrector for Igbo language designed using various n-grams, namely Trigrams and Bigrams.

A Trie is used for detection of the error word

Error Correction Trigrams use two words around the error word to find a possible candidate-list of words that can replace the error-word depending on the context. Bigrams use one word around the error word

Trigrams: Tri-right -> Uses the two words to the right Tri-left -> Uses the two words to the left Tri-center-> Uses the two words side by side of the error word

Bigrams: Bi-right -> Uses the word to the right Bi-left -> Uses the word to the left

All models are them combined to correct an error word based on its context, by giving a surrounding use of the context of the error word to correct it.



How to Use
- Create a Folder in the directory
- Name it "data"
- Add your .txt dataset in it.
- Run notebooks accordingly from 1 to 5
