# Getting Started with Voyant Tools
In this workshop we will explore utilizing the Voyant Tools platform originally developed by Stéfan Sinclair to analyze various texts and explore how textual analysis tools like Voyant can help advance your teaching and research. The exploration that we do today will also help you begin to build a foundation for utilizing more advanced text analysis tools if you wish to explore further. 

## What You'll Do
1. Familiarize yourself with the Voyant interface and analyze a historical novel of your choice
2. Complete some basic cleaning of your textual data and improve your results by updating a list of stopwords

## Why It Matters
Given recent trends in digitalization, there is a wealth of textual data available for analysis, both contemporary and historical. While textual analysis has long been used as a tool in literary studies, it also has important applications in a wide variety of domains ranging from the history of science to sociology. Using computational tools to analyze the written record can open up a wide variety of analytical avenues, including into understanding the nature of our own disciplines. Andrew Goldstone and Ted Underwood, for instance, analyzed over 21,000 peer-reviewed articles from *PMLA* in order to trace changes in the field of literary studies over the past 120 years. 

## Instructions
### Voyant Tools
For this workshop, we'll be using a free, web-based, open-source tool for text analysis. Originally developed by Stéfan Sinclair, Voyant Tools is currently led by Geoffrey Rockwell at the University of Alberta. It is one of the most accessible text analysis tools available and, because it is web-based and requires no special software, it is one of the easiest tools to begin to use for either research or teaching. While it is among the more basic text analysis tools available, it does offer some powerful analytical features and is useful for exploring texts and smaller *corpora*, or collections of texts, and serves as a useful gateway into the world of text analysis tools.

## Task One: Novel Analysis

### Step 1: Choose Your Text
Go to the [Project Gutenberg website](https://www.gutenberg.org/) and find a historical novel that you'd like to analyze. I'll be working with the full text of Mary Shelley's *Frankenstein* (https://www.gutenberg.org/). Make sure that you select the HTML5 version of whichever book you choose. You can either copy and past the full text of the novel *or* copy the link of the page with the full text. **Copy either the full text or the url for the full text site.**

## Step 2: Upload it to the Voyant Tools Site and Run the Initial Analysis
Now  go to the [Voyant Tools website](https://voyant-tools.org/) and copy and past either the full text or the URL of the full text site into the "Add Texts" box in the middle of the page. Click "Reveal." 

This will generate the default analysis of the text. You can see that there is a WordCloud, a reader with the (searchable) text in it. A trend graph of the most common terms, a summary pane, and a context pane that shows a "frame" of the words appearing to both the left and right of specific terms. We can see, for instance, that in the case of *Frankenstein*, the most common word in the novel is "man," followed by "life," "father," "shall," and "eyes." While this is very basic information about the terms that comprise the text, it might open up some interesting avenues for exploration. Certainly questions of humanity, life, and fatherhood are frequent well explored among Shelley's readers, but what about vision/visibility ("eyes") and commands/commandments ("shall")?

### Text Cleaning—Remove Stopwords
If you glance through the wordcloud for a book from Project Gutenberg, you may notice the term "Gutenberg" as one of the terms. This is not because your novel is particularly concerned with the origins of print, but rather because the full text versions from Project Gutenberg include the words "project" and "gutenberg" in the beginning and ending information of the text. This kind of textual "noise" is a common issue in text analysis applications and often the textual data that you use requires some cleaning to get it ready for analysis. There are a lot of techniques for  **Stopwords** are common words that you want to filter out from the analysis. Words like *the* and *and* appear frequently in English texts and carry relatively little semantic meaning in most textual analysis contexts. It is often useful to eliminate them from the textual data that you are working with to help ensure that 

## Step Two: Corpus Analysis

## Step Three: Brainstorm Utilization

## Options for Further Exploration
There are a wide variety of open source textual analysis packages that work with languages such as R and Python that enable everything from extracting topics and topical patterns to measuring sentiment within documents. If you're interested in exploring more, you can take a look at some of the following resources (many of which teach very well): 
- [Introduction to 
stylometry in Python](https://programminghistorian.org/en/lessons/introduction-to-stylometry-with-python) on [The Programming Historian](https://programminghistorian.org/) by François Dominic Laramée. 
- [Sentiment Analysis for Exploratory Data Analysis](https://programminghistorian.org/en/lessons/sentiment-analysis) on [The Programming Historian](https://programminghistorian.org/) by Zoë Wilkinson Saldaña. 

There are also great resources available for building corpora, including: 
- ITHAKA's [Constellate](https://constellate.org/) platform for academic articles
- [The HathiTrust Research Center](https://www.hathitrust.org/htrc) for historical books and periodical publications
- [Project Gutenberg](https://www.gutenberg.org/) for historical books that are no longer covered by copyright

## Sources
Goldstone, Andrew and Ted Underwood. "The Quiet Tranformation of Literary Studies: What Thirteen Thousand Scholars Could Tell Us." *New Literary History* 45, no. 3 (2014): 359-384.

Sinclair, Stéfan and Geoffrey Rockwell. Voyant Tools. 2016. http://voyant-tools.org/. 