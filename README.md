# simple_name_pairing
Pair names of entities using simple tuned metrics

. ~/anaconda3/bin/activate simple_name_pairing

Uses https://github.com/seatgeek/fuzzywuzzy to match the string-pairs you provide (learning from all the other pairs we can generate that cannot be a match), by creating a decision function that separates the two sets. Use the resulting function to match future data.
