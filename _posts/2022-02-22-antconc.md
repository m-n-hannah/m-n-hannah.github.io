---
title:  "Antconc"
mathjax: true
layout: post
categories: workshops, digital humanities
---
Unzip the download if necessary, and launch the application. 

Sample Corpus: Download and extract the zip file of Austen novels.

Navigate to [Antconc](https://www.laurenceanthony.net/software/antconc/)

Select your operating system:

![antconc1](https://user-images.githubusercontent.com/22083340/156229213-3f5765b2-6b39-4141-9550-3a914838435e.png)

There are 7 tabs across the top: 

![antconc2](https://user-images.githubusercontent.com/22083340/156229626-673ad419-1436-44b4-82ef-778eac88bfea.png)

Concordance: This will show you what’s known as a Keyword in Context view (abbreviated KWIC, more on this in a minute), using the search bar below it. 

Concordance Plot: This will show you a very simple visualization of your KWIC search, where each instance will be represented as a little black line from beginning to end of each file containing the search term. 

File View: This will show you a full file view for larger context of a result. 

Clusters: This view shows you words which very frequently appear together. 

Collocates: Clusters show us words which _definitely _appear together in a corpus; collocates show words which are statistically likely to appear together. 

Word list: All the words in your corpus. 

Keyword List: This will show comparisons between two corpora.

##Performing Analysis
1.	File > Create Quick Corpus

![antconc3](https://user-images.githubusercontent.com/22083340/156230027-28080ca9-cdac-40b8-9f3a-d266736ed687.png)

2.	Navigate to corpus folder

3.	Have a look at the tool settings. 

![antconc5](https://user-images.githubusercontent.com/22083340/156230630-a2f39085-2bd4-4424-aa0d-8e344ea55315.png)

4.	Start with a basic search. Key words in context will search for the words either to the left, right, or both of the search term.

![antconc4](https://user-images.githubusercontent.com/22083340/156230251-aef4a804-061a-4697-a120-bbed6f923aeb.png)

5.	Try searching using |

6.	Try searching for collocates, words associated with our search term.

![antconc6](https://user-images.githubusercontent.com/22083340/156230888-8bfeecba-df19-41da-bb5d-481325ac0727.png)

7. You can also look at ngrams where "n" equals number of words directly adjacent to your search word.

8.	Try comparing corpora. Select corpus manager and Target Corpus.

![antconc7](https://user-images.githubusercontent.com/22083340/156231220-431a5a39-712a-4e9b-9837-830f7f99597c.png)

9. Select Raw Files and Add Directory from the Raw Files Corpus Manager. Click Create.

![antconc8](https://user-images.githubusercontent.com/22083340/156231429-5d6f3af5-e7d7-44be-9d3e-414beb796947.png)

10. Now do the same for the Reference Corpus.

11. Click Create.

10.	A note on statistics. Keyness: this is the frequency of a word in the text when compared with its frequency in a reference corpus, “such that the statistical probability as computed by an appropriate procedure is smaller than or equal to a p value specified by the user.” For those interested in the statistical details, see the section on keyness on p7 of Laurence Anthony’s [readme file](https://www.laurenceanthony.net/software/antconc/releases/AntConc311/help.pdf).


