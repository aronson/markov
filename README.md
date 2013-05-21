markov
======
A ruby markov chain generator.

There are several generators that will generate different types of chains:
* Neologism will take words and create new words from them.
* Paragraph probably creates chains of sentences, though I don't really know
* Text just creates chains of words without sentence structure
* I don't even really know what word does

You first analyze stuff that you'd place in either txt/words or txt/texts
* Words is for collections of words to use in neologisms
* Texts are for when you want to add sentence structure to your markov chains

A good example to create some fun sentences of order 7:
    ruby anaylze Sentences 7 < txt/texts/*.txt > output.txt
    
When I learn markup better, I'll figure out how to explain the syntax of each command
