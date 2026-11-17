import nltk
from nltk.stem import PorterStemmer
ps = PorterStemmer()
print("PORTER STEMMER ALGORITHM")
print("-------------------------------")
n = int(input("Enter number of words: "))
words = []
for i in range(n):
    word = input("Enter a word: ").lower()
    words.append(word)
print("\nOriginal Word\tStemmed Word")
print("-------------------------------")
for word in words:
    stem = ps.stem(word)
    print(word, "\t\t", stem)
print("-------------------------------")
print("Stemming completed successfully!")
<img width="881" height="441" alt="Screenshot 2026-11-17 083430" src="https://github.com/user-attachments/assets/4252e44b-95cb-4ec8-b19a-a19ab6587729" />
