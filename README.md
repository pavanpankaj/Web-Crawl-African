# WebCrawl African
WebCrawl African is a collection of African Multilingual parallel corpora comprising of 6.95 lakhs (approx) sentence pairs, covering 15 African languages plus English and 73 language pairs. African languages covered include Afrikaans - afr, Lingala - lin, Swati - ssw, Amharic - amh, Luganda - lug, Tswana - tsn, Chichewa - nya, Hausa - hau, Oroma - orm, Xhosa - xho, Igbo - ibo, Xitsonga - tso, Yoruba - yor, Swahili - swh, Zulu - zul. 

This corpora is submitted as part of Large Scale Multilingual African Shared task Organized by WMT 2022. Thanks to Organizers for hosting the shared task. 

It covers variety of domains political, stories, religious and songs. Corpora have sentences covering both formal and informal writing styles. 

# Dataset Format

**African language, English parallel corpus**: Parallel corpus is located at data/African_English_parallel_corpora

**African language, African language parallel corpus**: Parallel corpus is located at data/African_African_parallel_corpora

Naming convention for src-lang, tgt-lang parallel corpus: 

Source language file : webcrawl-african-{src-lang}-{tgt-lang}.{src-lang}

Target langauge file : webcrawl-african-{src-lang}-{tgt-lang}.{tgt-lang}

Example:  
         
         For Afrikaans, Amharic parallel corpus 
         Source language file: webcrawl-african-afr-amh.afr
         Target language file: webcrawl-african-afr-amh.amh

# Statistics:

Table 1: Statistics of African-English parallel corpus {column : source-language} (Value is in multiple of thousand's(K))

African Language | #English |
--- | --- | 
afr | 62.2 |
amh | 4.6 |
nya | 1.4 |
hau | 5.6 |
ibo | 1.1 |
orm | 7.0 |
swh | 64.5 |
ssw | 14.4 |
tsn | 25.9 |
lin | 1.1 |
lug | 3.6 |
xho | 46.2 |
tso | 24.4 |
yor | 6.3 |
zul | 50.9 |
Total | 319.7 |


Table 2: Statistics of African-African parallel corpus from {column: source-language}, {row: target-language} (Value is in multiple of thousand's(K))

Language |Afrikaans | Amharic | Chichewa | Hausa | Igbo | Luganda | Oroma | Setswana | Swahili | Swati | Xhosa | Xitsonga | Yoruba | Zulu
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |--- | --- | --- | --- |
Afrikaans | -	| 2.537	| 0.955	| 2.591	| 0.155	| 2.068	| 3.338	| 18.753	| 13.680	| 10.994	| 33.465	| 19.681	| 3.071	| 32.813
Amharic	| 2.536	| -	| 0.634	| 2.562	| 0.117	| 1.650	| 2.816	| 0.000	| 3.130	| 0.091	| 0.000	| 0.000	| 2.792	| 0.000
Chichewa	| 0.955	| 0.634	| -	| 0.920	| 0.169	| 0.987	| 0.947	| 0.000	| 0.964	| 0.136	| 0.000	| 0.000	| 0.920	| 0.000
Hausa	| 2.591	| 2.562	| 0.920	| -	| 0.122	| 2.175	| 3.896	| 0.000	| 3.747	| 0.085	| 0.000	| 0.000	| 4.152	| 0.000
Igbo	| 0.155	| 0.117	| 0.169	| 0.122	| -	| 0.168	| 0.161	| 0.000	| 0.174	| 0.119	| 0.000	| 0.000	| 0.142	| 0.000
Luganda	| 2.068	| 1.650	| 0.987	| 2.175	| 0.168	| -	| 2.139	| 0.000	| 2.130	| 0.116	| 0.000	| 0.000	| 2.266	| 0.000
Oroma	| 3.338	| 2.816	| 0.947	| 3.896	| 0.161	| 2.139	| -	| 0.000	| 4.583	| 0.123	| 0.000	| 0.000	| 4.333	| 0.000
Setswana	| 18.753	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| -	| 0.000	| 11.140	| 19.694	| 19.442	| 0.000	| 18.904
Swahili	| 13.680	| 3.130	| 0.964	| 3.747	| 0.174	| 2.130	| 4.583	| 0.000	| -	| 0.133	| 0.000	| 0.000	| 4.134	| 0.000
Swati | 10.994	| 0.091	| 0.136	| 0.085	| 0.119	| 0.116	| 0.123	| 11.140	| 0.133	| -	| 11.274	| 11.515	| 0.118	| 11.139
Xhosa	| 33.465	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 19.694	| 0.000	| 11.274	| -	| 20.449	| 0.000	| 33.638
Xitsonga	| 19.681	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 19.442	| 0.000	| 11.515	| 20.449	| -	| 0.000	| 20.342
Yoruba	| 3.071	| 2.792	| 0.920	| 4.152	| 0.142	| 2.266	| 4.333	| 0.000	| 4.134	| 0.118	| 0.000	| 0.000	| -	| 0.000
Zulu	| 32.813	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 0.000	| 18.904	| 0.000	| 11.139	| 33.638	| 20.342	| 0.000	| - 
Total | 144.100   | 16.328	| 6.632	| 20.250	| 1.327	| 13.699	| 22.336	| 87.933 | 32.675 | 56.983| 118.520| 91.429	| 21.928	| 116.836 



# Models:

Models will be available soon.

# Effect of Inclusion of WebCrawl African:
We trained NMT model with and without inclusion of WebCrawl African Corpora. Results are given in below table

Table 3: BLEU score with and without WebCrawl African parallel corpus

African Language -> en | #W/O WebCrawl | #With WebCrawl |  
--- | --- | --- | 
afr | **55.8** | 55.73 |
amh | **24.39** | 24.17 |
nya | 22.45 | **22.66** |
hau | 27.92 | **28.04** |
ibo | 20.62 | **21.25**
kam | 9.24 | **9.49** |
kin | 25.97 | **26.15** |
lin | 19.34 | **19.56** |
lug | 15.93 | **16.69** |
luo | **17.34** | 16.96 |
fuv | 5.62 | **5.82** |
nso | 33.30 | **33.54** |
orm | 11.27 | **12.13** |
sna | **23.68** | 23.57 |
som | **18.01** | 17.80 |
swh | 41.01 | **41.19** |
ssw | 23.68 | **25.34** |
tsn | 22.66 | **23.08** |
xho | 31.8 | **32.01** |
tso | **24.32** | 21.72 | 
yor | 15.38 | 15.38 |
zul | 33.4 | **33.79** |
Avg | 22.39 | **22.50** |

For further details please visit the below articles

# Updates:
First Release (WebCrawl-African V1.0) : 10th May 2022

# Contributors:
Pavanpankaj Vegi (pavanpankaj333@gmail.com) 

Sivabhavani J

Biswajit Paul (biswajit07@gmail.com)

Abhinav Mishra

Prashant Banjare

# Acknowledgments
Prasanna Kumar K R

Chitra Viswanathan

**Source Websites** 

1.https://nalibali.org/

2.https://www.gov.za/ (posts/articles collected from 2016 onwards)

3.https://www.gotquestions.org/

4.https://africangospellyrics.com/



# License:

Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

# Citation

@InProceedings{vegi-EtAl:2022:WMT1,

  author    = {Vegi, Pavanpankaj  and  J, Sivabhavani  and  Paul, Biswajit  and  Mishra, Abhinav  and  Banjare, Prashant  and  K R, Prasanna Kumar  and  Viswanathan, Chitra},
  
  title     = {WebCrawl African : A Multilingual Parallel Corpora for African Languages},
  
  booktitle      = {Proceedings of the Seventh Conference on Machine Translation},
  
  month          = {December},
 
  year           = {2022},
  
  address        = {Abu Dhabi},
  
  publisher      = {Association for Computational Linguistics},
  
  pages     = {1076--1089},
  
  url       = {https://aclanthology.org/2022.wmt-1.105}

}

@InProceedings{vegi-EtAl:2022:WMT2,
  
  author    = {Vegi, Pavanpankaj  and  J, Sivabhavani  and  Paul, Biswajit  and  K R, Prasanna Kumar  and  Viswanathan, Chitra},
  
  title     = {ANVITA-African: A Multilingual Neural Machine Translation System for African Languages},
  
  booktitle      = {Proceedings of the Seventh Conference on Machine Translation},
  
  month          = {December},
  
  year           = {2022},
 
  address        = {Abu Dhabi},
  
  publisher      = {Association for Computational Linguistics},
  
  pages     = {1090--1097},
  
  url       = {https://aclanthology.org/2022.wmt-1.106}

}

# Note:
Data sources used for this corpora are duly acknowledged under the Acknowledgments section above. Data is collected following the source website usage/copyright T&C. We do not own any of the text. 


