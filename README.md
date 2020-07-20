# Neural Machine Translation

## A Neural Machine Translation (NMT) model to translate human-readable dates ("25th of June, 2009") into machine-readable dates ("2009-06-25")
## Created using an attention model, one of the most sophisticated sequence-to-sequence models. 

* Input dates written in a variety of possible formats (e.g. "the 29th of August 1958", "03/30/1968", "24 JUNE 1987") 
* The model will translate them into standardized, machine readable dates (e.g. "1958-08-29", "1968-03-30", "1987-06-24"). 
* We will have the network learn to output dates in the common machine-readable format YYYY-MM-DD. 
* We will visulaize the attention
