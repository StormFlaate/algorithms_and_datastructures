# Hvorfor er det en nedre grense for kompleksiteten til sammenligningsbaserte algoritmer?

Forestill deg et sammenligningstre, slik som treet på side 192 i boka. Den maksimale høyden til dette treet er 3,
og det er 6 løvnoder. Dette sammenligningstreet sammenligner tallene i en liste med 3 tall.
Det er 3!=6 ulike permutasjoner av inputet, så det minste antallet løvnoder er 6.

Så n = 3  
h = 3  
antall løvnoder = 6  

Det maksimale antallet løvnoder vi kan ha, er 2^h = 2^3 = 8
Det minste antallet løvnoder er n! = 6

Vi vil finne høyden til treet, fordi høyden gir oss antallet sammenligninger vi må gjøre for å sortere listen.
(Hvert nivå er en sammenligning).

Dette kan vi finne ved å løse  
2^h >= n!  
lg2^h >= lg(n!)  
h*lg2 >= n lg(n)  
h >= n lg(n)  

<https://www.youtube.com/watch?v=WffUZk1pgXE&ab_channel=BackToBackSWE>
