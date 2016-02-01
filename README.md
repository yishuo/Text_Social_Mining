<h1>Data Mining (Text Minging + Social Mining)</h1>
<h3>This is my project of Data mining.</h3>
<p><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/Cas2015_16.xlsx">This file<a> is my original data, which describes 1041 articles published in the conference EGC since 2014.</p>
<p>Each record (line), corresponds to an article represented by 8 attributes:</p>
<p>series, booktitle, year, title, abstract, author, pdf1page, pdfarticle.<p>
<p>Only 896 articles have an abstract.<p>

<h5>The problem that I defined is a problem in relation with the lessons of text mining or social mining lessons:</h5>
<p>--Analyse a graph of the documents where there is a link between two documents if they share a great number of words</p>

<p><h5>Idea</h5>Here, we analysed the data from 'abstract' and just tested 20 articles.</p>

<p>The description of every file is :</p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/pretraitement_textMining.r">pretraitement_textMining.r:</a></h6>We extracted the data of 'abstract' from file.xlsx and preprocess teh data by Text mining (delete the whitespace, numbers and punctuation, Tolower,  stopwords and sparse etc.).</p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/socialMining.r">socialMining.r:</a></h6>
We process the data that we extracted in the first step and find the multifrequence related words </p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/bipartite.r">bipartite.r:</a></h6>
We extracted 20 articles exemples from the data we extracted in the first step and make a bi-directional graph.</p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/plot_analyse.r">plot_analyse.r:</a></h6>
We extracted 20 articles exemples from the data we extracted in the second step and plot the directional and no directional graphs (According to related words of two articles). </p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/result.csv">result.csv:</a></h6>The result of the first step.</p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/table.csv">table.csv:</a></h6>The result of the directional graph.</p>
<p><h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/tableno.csv">tableno.csv:</a></h6>The result of the no directional graph.</p>
<h6><a href="https://github.com/yishuo/Text_Social_Mining/blob/master/Projet_EGC_ZunzunWANG_YishuoLYU.pdf">Projet_EGC_ZunzunWANG_YishuoLYU.pdf:</a></h6><p>The report of this project.</p>

