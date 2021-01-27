# kd-wrangle

## Assigned Play 
[Love's Labours Lost](http://shakespeare.mit.edu/lll/full.html)

## Speaker 1
Biron

## Speaker 2
Dumain

## Question
Count of each speaker with less or more?

## Commands Used in Bash
- ```$ curl "http://shakespeare.mit.edu/lll/full.html" | sed 's/<\/*[^>]*>//g' > kd.txt```
- ```$ grep '^BIRON$' kd.txt -c > biron_count.txt```
- ```$ grep '^DUMAIN$' kd.txt -c > dumain_count.txt```

## Answer
Biron speaks more with count(158) and Dumain speaks less with count(54).
