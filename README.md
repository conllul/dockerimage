# CoNLL-UL Docker Image

This repository holds the Dockerfile and associated tools for the [CoNLL-UL Docker](https://hub.docker.com/r/habeanf/conllul/).

If you want to add a morphological analyzer, take a look at `dispatch/he.py` or `dispatch/tr.py`, and add your script to `dispatch/analyzers.py`

If you have a morphological *lexicon*, you need only add it to `/home/gopath/src/yap/data` with the file name format `UDLex_<language>-<lexicon>.conllul` (like `UDLex_English-Apertium.conllu`), and the image will take care of the rest.

For more information on CoNLL-UL, see the [homepage](https://conllul.github.io) or [publication](http://www.lrec-conf.org/proceedings/lrec2018/pdf/625.pdf)
