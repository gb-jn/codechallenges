# Over The Wire - Bandit Server Notes
ssh bandit.labs.overthewire.org -p 2220 -l bandit0

## Bandit 0  
bandit0

## Bandit 1  
boJ9jbbUNNfktd78OOpsqOltutMc3MY1  

## Bandit 2  
CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9  

## Bandit 3  
UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK  

## Bandit 4  
password  
pIwrPrtPN36QITSp3EQaw936yaFoFgAB  

solution for finding next password    
for i in \`ls -1 .`; do cmd="file ./$i"; $cmd; done  

## Bandit 5  
password  
koReBOKuIDDepwhWk7jZC0RTdopnAYKh  

solution for finding next password    
find -size 1033c  

## Bandit 6  
password  
DXjZPULLxYr17uwoI01bNLQbtFemEgo7  

solution for finding next password    
cat `find / -size 33c -group bandit6 -user bandit7 2>/dev/null`

## Bandit 7
password  
HKBPTKQnIay4Fw76bEy8PVxKEDQRKTzs  

solution for finding next password  
grep millionth data.txt  

## Bandit 8  
password  
cvX2JJa4CFALtqS87jk27qwqGhBM9plV  

solution for finding next password  
sort data.txt | uniq -u

## Bandit 9  
password  
UsvVyFSfZZWbi6wgC7dAFyFuR6jQQUhR  

solution for finding next password  
strings data.txt | grep =======  

## Bandit 10  
password  
truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk  

solution for finding next password  
base64 -d data.txt  

## Bandit 11  
password  
IFukwKGsFW8MOq3IRFqrxE1hxTNEbUPR  

solution for finding next password  
tr 'a-zA-Z' 'n-za-mN-ZA-M' < data.txt  

## Bandit 12  
password  
5Te8Y4drgCRfCx8ugdwuEX8KFC6k2EUu  

solution for finding next password  
