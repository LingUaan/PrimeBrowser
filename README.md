# PrimeBrowser
As the title says, you can browse prime number tables conviniently with a graphical UI.


Usage
=====

Download the program, unzip it anywhere and run it by clicking the program item.


Tables
====== 
  
All entries were compared with the extensive prime sieve tables of Tomás Oliveira e Silva and Jan Büthe, where available.<br/>
All other entries were double checked, except table 1d23. So I'm quite confident that the results up to table 1d22 are correct.<br/>
Table 1d23 has at least two errors as the li(x)-pi(x) result indicates. double check for table 1d23 pending.

  
Table            | pi(x) generated with | li(x) generated with
------------------- | -------- | --------
  1d09	| program LingSieve of myself	| boost
  1d10	| previous table	| boost
  1d11 	| program LingSieve of myself (blue/white)	| boost
  1d12 	| previous table	| boost
  1d13 	| previous table	| boost
  1d14 	| previous table	| boost
  1d15 	| program primecount of Kim Walisch (green/white)	| primecount
  1d16 	| previous table	| primecount
  1d17 	| previous table	| primecount
  1d18 	| previous table	| primecount
  1d19 	| program primecount of Kim Walisch (purple/white)	| primecount
  1d20 	| previous table	| primecount
  1d21 	| previous table	| primecount
  1d22 	| previous table	| primecount
  1d23 	| program primecount of Kim Walisch	(pink/white) | primecount
  
  
  
  
  Status
  ======
  
  Basic development is finished, tables hold more than 10 million records and counting ...<br/>
  Program with DB can't be uploaded, even in zipped form it exceeds 170MB, whereas GitHub allows 25MB only.<br/>
  After emptying tables d11 and d12 the program size is small enough to be uploaded.
