# Time-in-Words---Using-Inflect-module
## Conversion of time into words Using the inflect Module in Python
**_inflect.py_**
*Inflection is a String transformation library.*
*It helps in various ways like*
>1. convert numbers to words.
>2. Generating plurals,singular nouns,ordinals and  indefinite articles
### Installation
In Ubuntu
For python version 2 - ```$ pip install inflect```

For python version 3 -``` $ pip3 install inflect```
 
Or Directly refer to https://pypi.python.org/pypi/inflect

### How to use 
```
import inflect

p = inflect.engine()

#Conversion of numbers into words

  p.number_to_words(n)
  
#Converting in Plural form
 
  p.plural(word)
  
#Converting in Singular form

 p.singular_noun(word)
 
#Comparisons

 p.compare(word1, word2)
 p.compare_nouns(word1, word2)
 p.compare_verbs(word1, word2)
 p.compare_adjs(word1, word2)
 
#Adding Correct a or an in the given word or sentence

 p.an(idea)
 p.a(thing)



```



