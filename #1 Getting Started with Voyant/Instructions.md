# Getting Started with Voyant Tools
In this workshop we will explore utilizing the Voyant Tools platform originally developed by Stéfan Sinclair to analyze various texts and explore how textual analysis tools like Voyant can help advance your teaching and research. The exploration that we do today will also help you begin to build a foundation for utilizing more advanced text analysis tools if you wish to explore further. 

## What You'll Do
1. Familiarize yourself with the Voyant interface and analyze a historical novel of your choice
2. Complete some basic cleaning of your textual data and improve your results by updating a list of stopwords
3. Upload and analyze a corpus of scholarly journal article data
4. Identify possible teaching or research applications that you might be able to apply 

## Why It Matters
Given recent trends in digitalization, there is a wealth of textual data available for analysis, both contemporary and historical. While textual analysis has long been used as a tool in literary studies, it also has important applications in a wide variety of domains ranging from the history of science to sociology. Using computational tools to analyze the written record can open up a wide variety of analytical avenues, including into understanding the nature of our own disciplines. Andrew Goldstone and Ted Underwood, for instance, analyzed over 21,000 peer-reviewed articles from *PMLA* in order to trace changes in the field of literary studies over the past 120 years. 

## Instructions
### Voyant Tools
For this workshop, we'll be using Voyant, a free, web-based, open-source tool for text analysis. Originally developed by Stéfan Sinclair, Voyant Tools is currently led by Geoffrey Rockwell at the University of Alberta. It is one of the most accessible text analysis tools available and, because it is web-based and requires no special software, it is one of the easiest tools to begin to use for either research or teaching. While it is among the more basic text analysis tools available, it does offer some powerful analytical features and is useful for exploring texts and smaller *corpora*, or collections of texts, and serves as a useful gateway into the world of text analysis tools.

## Task One: Novel Analysis

### Step 1: Choose Your Text
Go to the [Project Gutenberg website](https://www.gutenberg.org/) and find a historical novel that you'd like to analyze. I'll be working with the full text of Mary Shelley's *Frankenstein* (https://www.gutenberg.org/). Make sure that you select the HTML5 version of whichever book you choose. You can either copy and past the full text of the novel *or* copy the link of the page with the full text. **Copy either the full text or the url for the full text site.**

## Step 2: Upload it to the Voyant Tools Site and Run the Initial Analysis
Now  go to the [Voyant Tools website](https://voyant-tools.org/) and copy and past either the full text or the URL of the full text site into the "Add Texts" box in the middle of the page. Click "Reveal." 

This will generate the default analysis of the text. This analysis consists of a series of five panes, each of which features a particular text analysis tool. We'll explore these options later in the workshop, but you can see a full list of the available tools in Voyant [here](https://voyant-tools.org/docs/#!/guide/tools_). 

![Voyant Tools Default Analysis Interface](https://github.com/bkrien/TeachTextTech/blob/main/Images/VoyantInterface.png?raw=true)

You can see that there is a WordCloud, a reader with the (searchable) text in it. A trend graph of the most common terms, a summary pane, and a context pane that shows a "frame" of the words appearing to both the left and right of specific terms. We can see, for instance, that in the case of *Frankenstein*, the most common word in the novel is "man," followed by "life," "father," "shall," and "eyes." While this is very basic information about the terms that comprise the text, it might open up some interesting avenues for exploration. Certainly questions of humanity, life, and fatherhood are frequent well explored among Shelley's readers, but what about vision/visibility ("eyes") and commands/commandments ("shall")?

### Text Cleaning—Remove Stopwords
If you glance through the wordcloud for a book from Project Gutenberg, you may notice the term "Gutenberg" as one of the terms. This is not because your novel is particularly concerned with the origins of print, but rather because the full text versions from Project Gutenberg include the words "project" and "gutenberg" in the beginning and ending information of the text. This kind of textual "noise" is a common issue in text analysis applications and often the textual data that you use requires some cleaning to get it ready for analysis. There are a lot of techniques for cleaning textual data, but we'll focus on one of the most basic—removing stopwords.

 **Stopwords** are common words that you want to filter out from the analysis. Words like *the* and *and* appear frequently in English texts and carry relatively little semantic meaning in most textual analysis contexts. It is often useful to eliminate them from the textual data that you are working with to help ensure that you get the most meaningful possible results. There are a number of lists of default stopwords used in various textual analysis applications, but it is often helpful to add words that reflect the specific context of the text or texts with which you're working. 

 If you hover over the top right corner of the top left wordcloud pane, you will see a small toggle switch. This allows you to adjust the options for the tool in this particular pane. Click to toggle. This will bring up the options window for this particular pane/tool. 
 
 ![Voyant Tools Default Analysis Interface](https://github.com/bkrien/TeachTextTech/blob/main/Images/VoyantOptions.png?raw=true)

 The first option should be "Stopwords" and there should be an "Edit List" button next to it. Click this and add "project" and "gutenberg" on separate lines in the list. Save it and make sure that the "apply globally" box is checked. Not click confirm and you should see that neither "project" nor "gutenberg" are included in the wordcloud anymore. Because you applied the change globally, they will also be excluded from other analyses (though they will still appear in the reader). 

## Task Two: Corpus Analysis
Now that we've taken a look at the basic functionality of Voyant, we're going to dig into some of it's more powerful features, namely it's ability to analyze a corpus of texts. We're going to look at a sample set of articles from the *American Historical Review* that are drawn from ITHAKA's Constellate platform. These articles were all published between 1900 and 2016 (there are 1500 total) and we're going to look to see if they reveal any trends in historical scholarship during that period. 

### Step One: Download the Corpus
The first thing that you're going to want to do is download the data files. There are 12 files, each for a decade's word of articles. You can download each of these files individually here on GitHub (time-consuming) or download them from this shared [Google Drive](https://bit.ly/VoyantCorpus) (fast). Make sure that you have files 1900.txt through 2010.txt. 

> **Note:** These files have already have the stopwords removed, so you don't need to worry about removing the main lists, through you can move additional words that might clutter your analysis (like "pp" that snuck in because of the page numbers). 

### Step Two: Upload the Corpus
Now that you have all the files downloaded, you're going to need to upload them to Voyant. Open up a new Voyant tab and hit the "Upload" button. You're going to select all of the files and upload them all at once. This will take a minute because these files are quite large (representing a total of 11,901,087 tokens!).

### Step Three: Analyze
Once the corpus loads, you can explore the visualizations. Get started with the "Trends" tool/pane in the top right. Start by typing the word "women" or "wom*" (or both) in the terms box at the bottom left of the Trends pane. The results will show you the relative frequency of the word women relative to the other words in the corpus during each decade (the timeline along the botton will automatically be populated because of the names of the files, but make sure that it's in the correct order).

What other trendscan you find by exploring the data

## Task Three: Brainstorm Utilization

For the final part of our time together, think about how you might be able to use this or other text analysis tools in either your research or teaching. Start by identifying texts or textual datasets that might be interesting (this could be anything from ancient codices to French-language newspapers to Twitter data) and then think about what kinds of analysis you would like to do. What's interesting about this data or these corpora? What would you like to learn more about? How might you be able to use this in your research or teaching? 

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

Krien, Brady. *American Historical Review Dataset.* March 2023. Distributed by Constellate. https://constellate.org/dataset/fc87e194-7f15-d88c-e593-4258313cdf56/

Sinclair, Stéfan and Geoffrey Rockwell. Voyant Tools. 2016. http://voyant-tools.org/. 