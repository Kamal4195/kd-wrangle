# kd-wrangle

## Assigned Task: 
[Love's Labours Lost](http://shakespeare.mit.edu/lll/full.html)

## Speaker-One:
Biron

## Speaker-Two:
Dumain

## Question: 
Count of each speaker with less or more?

## Commands which I used in Bash:
- ```$ curl "http://shakespeare.mit.edu/lll/full.html" | sed 's/<\/*[^>]*>//g' > kd.txt```
- ```$ grep '^BIRON$' kd.txt -c > biron_count.txt```
- ```$ grep '^DUMAIN$' kd.txt -c > dumain_count.txt```

## Answer to question:
Biron speaks more with count(158) and Dumain speaks less with count(54).
