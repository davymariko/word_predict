# word_predict
A program in OZ language that predicts next words while typing

It's a project I worked on with *Nicolas Jadoul* at "Univesrité Catholique de Louvain"

**Goal**

The fictional challenge was to give the USA President an alternative to time spent to his tweetings by predicting the next word while typing.
The goal was to provide a graphical application capable of predicting the next word he will write from the previous words. 
The mission was to automate the writing of its tweets based on a history of tweets provided.

Environment: Mozart
Preferable editor: Emacs or VSCode (for implemention of linux environment)

**Compilation**

Usable commands:

* ``make run`` : compile the program
* ``make clean``
* ``make all``


**Structure**

-> You can find information of the functions of the program in these files:

* ``main.oz``: synchronization of the threads and launches the program with the GUI interface
* ``Reader.oz``: read the tweets
* ``Parse.oz``: parse the tweets
* ``Dict.oz``: create the dictionaries containing the words and their prediction

<-

* ``Makefile``: contains the command to run the program
* ``tweets``: folder containing the tweets to assess

P.S: I added the project report which is in french.
