---
layout: article
title: Ten Simple Rules for Data Storage
tags: []
bibliography: resources/manuscript.bib
csl: resources/plos.csl
author:
 - family: Hart
   given: Edmund
   affiliation: 1
   email: emh@emhart.info
 - family: Barmby
   given: Pauline
   affiliation: 2
 - family: Hollister
   given: Jeffrey
   affiliation: 3
 - family: LeBauer
   given: David
   affiliation: 4
   
organization:
 - id: 1
   name: Univeristy of Vermont
   address: Department of Biology, Burlington
 - id: 2
   name: University of Western Ontario
   address: Department of Physics and Astronomy
 - id: 3
   name: US Environmental Protection Agency
   address: Atlantic Ecology Division
 - id: 4
   name: University of Illinois at Urbana-Champaign
   address: Institute for Genomic Biology
 - id: 5
   name: National Center for Supercomputing Applications

---

# Abstract {-}

\linenumbers

# Introduction {-}
Some example text with a citation [@goodman2014ten]

# Rule 1: Rule {-}

# Rule 2: Rule {Know your use case}

Researchers should know their use case and store data appropriately. Is this data collected and just being archived? Will it change regularly? How will those changes be logged (e.g. provenance if any)? Will this be shared via an API? Linked to a paper? What are the institutional restrictions? Can you use a commercial service like Dropbox or use a personally maintained system? Knowing the reason why you're sharing your data will constrain your choices here.

<!--
also see number 9, which will be aimed at big data
-->

# Rule 3: Rule {-}

# Rule 4: Rule {-}

# Rule 5: Rule {-}

# Rule 6: Rule {-}

# Rule 7: Rule {-}

# Rule 8: Rule {-}

# Rule 9: Rule {Data size matters /  requires special considerations}

* [#39](https://github.com/emhart/10-simple-rules-data-storage/issues/39) and related GH issues  [#16](https://github.com/emhart/10-simple-rules-data-storage/issues/16), [#19](https://github.com/emhart/10-simple-rules-data-storage/issues/16), [#25](https://github.com/emhart/10-simple-rules-data-storage/issues/25) 

<!---
refs #16, #19, #25


needs to be different than rule 2
-->

Data that is larger than memory can handle, or ...

raw data on server, cloud, or long term storage. Data for analysis (if small enough) can go on a fast access disk, like SSD.

Can be handled by 'big memory' nodes.

In many cases fast access between disk and compute server is needed, so that I/O doesn't bog down the entire process. If you have a big dataset and now I need to do some big computation with it" in which case you often want the disk with the data to be close to the machine doing the computation.

Data size matters. As @stephenturner points out there's a vast difference between data created by NEON and a data set you might archive on Figshare from your PhD (if you're an ecologist anyway). How you store your data has to take these size considerations. It will determine where you archive your data, how it's backed-up and how it's shared.

lemma 1: storage costs and transfer / compute time are trivial if data is small, but can add up if data is large. At some size, it is not practical to store data - there are trade offs among cost, information content, and accessibility.


* put data where and how you can compute on it, rather than moving raw datasets around



Covers proximity / mounting and architecture. Don't hog active space if slow storage is sufficient - scan for untouched files to put in longer term storage.

Don't move it around if you can help it. If you must, use appropriate tools, Store local 'cached' copies (eg use knitr argument) instead of writing scripts that always download archived data. Only do so if there are changes.

Do sub setting server-side, computing in database (dplyr lazy eval) etc.

---
 

Basically, the format for long-term archival is not the same format that is needed for day-to-day analysis. I'd say that in the opposite direction, actually: don't archive your data in the format that makes sense for you in your day-to-day use.


# Rule 10: Rule {-}



# Figure Legends {-}

Figures here:  Will need to figure out numbering...

# Tables {-}

Tables here:  Will need to figure out numbering...

\nolinenumbers

# References {-}
\bibdata{resources/manuscript.bib}
