#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I
a) runtime = (n * n * n)/(n * n) = n
this algorithm has a runtime of 0(n)

b) runtime = n * n * n * 10
this algorithm has a runtime of 0(n**3)

c) this algorithm has a runtime of 0(n)

## Exercise II

# run time complexity defined:

# takes in the argument of word and then check the length of the word if it's equal to 0 or less then 2 it will return 0 that is the break statement
# if it is more then 2 or 0 it will slice the word to look for the th in the array [0:2] ==‘th’ part. # if it finds the th in the string it will return the word with count if not it will return the word .



def count_th(word):
   word_leng = len(word)
   if word_leng == 0 or word_leng < 2:
       return 0
   elif word[0:2] == “th”:
       return count_th(word[1::]) + 1
   else:
       return count_th(word[1::])

