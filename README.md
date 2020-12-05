# PrimeBrowser
As the title says, you can browse prime number tables conviniently with a graphical UI.


Usage
=====

  Open a Command Prompt and run the program LingSieve:
  
  1) start without parameter - it will use initial values - StartValue (0), segment size (100") and start a LDT
  2) if there is a valid Result file it will use the last entry as StartValue, segment size (100") and start a LDT
  3) if there is a user input it will use it instead of 1) or 2)


  
  
Table            | Comment
------------------- | --------
  1d09		| generated with LingSieve
  LingSieve				             | Start LDT from 0 or from the last entry of file Result.txt if there is any
  LingSieve 0			          | Count the primes from 0 .. 10^11
  LingSieve 0 -s1		        | Count the primes from 0 .. 10^9
  LingSieve 0 -s10		      | Count the primes from 0 .. 10^10
  LingSieve 1000000		      | Count the primes from 10^15 .. 10^15+10^11
  LingSieve 100000000 -s1000	| Count the primes from 10^17 .. 10^17+10^12
  LingSieve /?			        | Display help text
  
  
  
  Status
  ======
  
  I've sifted 6,8x10^16 numbers in various ranges without any errors, that is 68.000.000 cycles. Once I run it for more than 60 hours continuously without any problems, it just works as it is supposed to. The results were compared with the extensive prime sieve tables of Tomás Oliveira e Silva and Jan Büthe, randomly with the program primesieve 64bit of Kim Walisch.
  
  
  Basic development is finished.
