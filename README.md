# Readability Calculator
------------------------

Readability calculator is a simple program to estimate how skilled a reader must be to understand a piece of text.
There is a large number of methods for that. The following ones are implemented in the current version of this program:

1. [Flesh Reading Ease] (http://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_test#Flesch_Reading_Ease)
2. [Flesh Kincaid Grade Level] (http://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_Grade_Level#Flesch.E2.80.93Kincaid_Grade_Level)
3. [Coleman Liau Index] (http://en.wikipedia.org/wiki/Coleman-Liau_Index)
4. [Gunning Fog Index] (http://en.wikipedia.org/wiki/Gunning-Fog_Index)
5. [SMOG Index] (http://en.wikipedia.org/wiki/SMOG)
6. [ARI Index] (http://en.wikipedia.org/wiki/Automated_Readability_Index)
7. [LIX Index] (http://en.wikipedia.org/wiki/LI)
8. [Dale-Chall Score] (http://en.wikipedia.org/wiki/Dale%E2%80%93Chall_readability_formula)

# Dependencies
-------------

* [Pyphen] (https://github.com/Kozea/Pyphen) 

```bash
> pip install pyphen
```

* [NLTK] (https://github.com/nltk/nltk)

```bash
> pip install nltk
> python
> import ntlk
> nltk.download("punkt")
```

# Using
--------

1. Download it ([Pypi link] (https://pypi.python.org/pypi/ReadabilityCalculator/)):
```bash    
> pip install ReadabilityCalculator
```
2. Using the library:
```python
from readcalc import readcalc
calc = readcalc.ReadCalc("This is a simple text.")
calc.get_smog_index()
> 3.1291
```

