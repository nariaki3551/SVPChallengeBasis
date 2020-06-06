# SVP Challenge Basis

Lattice basis files from the Darmstadt SVP Challenge (https://www.latticechallenge.org/svp-challenge/)



## Files

### dimXX/original/dimXXseedYY.txt

This is the original basis of dimension XX and seed YY obtained from SVP Challenge site.

### dimxx/BKZ20/dimXXseedYYBKZ20.txt

This is the basis for dimension XX and seed YY reduced by the BKZ algorithm with a block size of 20 of fplll library (https://github.com/fplll/fplll).

Command is `fplll basis_file -a bkz -b 20`

