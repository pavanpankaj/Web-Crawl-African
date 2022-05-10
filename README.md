# Web-Crawl-African
Web Crawl African is a collection of African langauge Multilingual parallel corpus in 16 langauges covering  Afrikaans - afr, Lingala - lin, Swati - ssw/Siswati,
Amharic - amh, Luganda - lug, Tswana - tsn/Setswana, Chichewa - nya, Hausa - hau, Oroma - orm, Xhosa - xho/isiXhosa, Igbo - ibo, Xitsonga - tso, Yoruba - yor, Kinyarwanda - kin, Swahili - swh, Zulu - zul/isiZulu. 

It is a part of Large Scale Multilingual African Shared task Organized by WMT 2022. Thanks to Organizers for hosting the shared task. 

It covers variety of domains political, general, songs and god.

# Dataset Format
Naming convention for Source Language, Target Language parallel corpus: 

Source language file : web-crawl-african-{src-lang}-{tgt-lang}.{src-lang}

Target langauge file : web-crawl-african-{src-lang}-{tgt-lang}.{tgt-lang}

Example:  
         
         For Afrikaans, Amharic parallel corpus 
         Source language file: web-crawl-african-afr-amh.afr
         Target language file: web-crawl-african-afr-amh.amh

# Statistics:

Table 1B: Statistics of parallel corpus {column : source-language}, english (Value is in multiple of thousand's(K))

Langauge | #en |
--- | --- | 
afr | 61.8 |
amh | 4 |
nya | 1.4 |
hau | --- |
ibo | 3.2 |
kin | --- |
orm | 7 |
swh | 62 |
ssw | 14.2 |
tsn | 25.3 |
lin | 1.1 |
lug | 3.6 |
xho | 51.4 |
tso | 24 |
yor | 6.3 |
zul | 50.7 |
Total | 316 |

Table 2B: Statistics of parallel corpus from {column: source-language}, {row: target-language} (Value is in multiple of thousand's(K))

Langauge | #afr | #amh | #nya | #hau | #ibo | #kin | #orm | #swh | #ssw | #tsn | #lin | #lug | #xho |#tso | #yor |#zul |
--- | --- | --- | --- |--- |--- |--- |--- |--- |--- |--- |--- | --- | --- | --- |--- |--- |
afr | --- | 2.5 | 0.95 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
amh | 2.5 | --- | 0.63 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
nya | 0.95 | 0.63 | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
hau | 2.5 | 2.5 | 0.9 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
ibo | 0.15 | 0.1 | 0.1 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
kin | --- | --- | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
orm | 3.33 | 2.8 | 0.9 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
swh | 13.6 | 3.1 | 0.9 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
ssw | 10.9 | 0.1 | 0.1 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
tsn | 18.6 | --- | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
lin | --- | --- | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
lug | 2.06 | 0.9 | 0.9 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
xho | 33.3 | --- | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
tso | 19.6 | --- | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
yor | 3.07 | 2.7 | 0.9 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
zul | 32.7 | --- | --- | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274
Total | 205 | 20 | 7.6 | 286 | 289 | 285 | 287 | 287 | 272 | 276 | 269 | 270 | 271 | 272 | 273 | 274


 Language |Afrikaans | Amharic | Chichewa | Hausa | Igbo | Luganda | Oroma | Setswana | Swahili | Swati | Xhosa | Xitsonga | Yoruba | Zulu
Afrikaans | 0.000	|2.536	|0.955	|2.591	|0.155	|2.068	|3.338	|18.753	|13.680	|10.994	|33.465	|19.681	|3.071	|32.813
Amharic	|2.536	|0.000	|0.634	|2.562	|0.117	|1.650	|2.816	|0.000	|3.130	|0.091	|0.000	|0.000	|2.792	|0.000
Chichewa	|0.955	|0.634	|0.000	|0.920	|0.169	|0.987	|0.947	|0.000	|0.964	|0.136	|0.000	|0.000	|0.920	|0.000
Hausa	|2.591	|2.562	|0.920	|0.000	|0.122	|2.175	|3.896	|0.000	|3.747	|0.085	|0.000	|0.000	|4.152	|0.000
Igbo	|0.155	|0.117	|0.169	|0.122	|0.000	|0.168	|0.161	|0.000	|0.174	|0.119	|0.000	|0.000	|0.142	|0.000
Luganda	|2.068	|1.650	|0.987	|2.175	|0.168	|0.000	|2.139	|0.000	|2.130	|0.116	|0.000	|0.000	|2.266	|0.000
Oroma	|3.338	|2.816	|0.947	|3.896	|0.161	|2.139	|0.000	|0.000	|4.583	|0.123	|0.000	|0.000	|4.333	|0.000
Setswana	|18.753	|0.000	|0.000	|0.000	|0.000	|0.000	|0.000	|0.000	|0.000	|11.140	|19.694	|19.442	|0.000	|18.904
Swahili	|13.680	|3.130	|0.964	|3.747	|0.174	|2.130	|4.583	|0.000	|0.000	|0.133	|0.000	|0.000	|4.134	|0.000
Swati |10.994	|0.091	|0.136	|0.085	|0.119	|0.116	|0.123	|11.140	|0.133	|0.000	|11.274	|11.515	|0.118	|11.139
Xhosa	|33.465	|0.000	|0.000	|0.000	|0.000	|0.000	|0.000	|19.694	|0.000	|11.274	|0.000	|20.449	|0.000	|33.638
Xitsonga	|19.681	|0.000	|0.000	|0.000	|0.000	|0.000	|0.000	|19.442	|0.000	|11.515	|20.449	|0.000	|0.000	|20.342
Yoruba	|3.071	|2.792	|0.920	|4.152	|0.142	|2.266	|4.333	|0.000	|4.134	|0.118	|0.000	|0.000	|0.000	|0.000
Zulu	|32.813	|0.000	|0.000	|0.000	|0.000	|0.000	|0.000	|18.904	|0.000	|11.139	|33.638	|20.342	|0.000	|0.000



# Models:

Models will be available after the shared task.

# Updates:

# Contributors:
Pavanpankaj Vegi

Sivabhavani J

Biswajit Paul

Abhinav Mishra

Prashant Banjare

{others}

# Acknowledgments

Prasanna Kumar K R

Director



{others}

# License:

# Citation

Citation will be available after the shared task

# Note:


