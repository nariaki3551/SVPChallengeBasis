# SVP Challenge Basis

Lattice basis files from the Darmstadt SVP Challenge (https://www.latticechallenge.org/svp-challenge/)

<br>
<br>

## Files

### dimXX/original/dimXXseedYY.txt

This is the original basis of dimension XX and seed YY obtained from SVP Challenge site.

### dimxx/BKZ20/dimXXseedYYLLL.txt

This is the basis for dimension XX and seed YY reduced by the LLL algorithm of fplll library (https://github.com/fplll/fplll) with version 5.2.1.

Command is `fplll basis_file -a lll`

### dimxx/BKZ20/dimXXseedYYBKZ20.txt

This is the basis for dimension XX and seed YY reduced by the BKZ algorithm with a block size of 20 of fplll library (https://github.com/fplll/fplll) with version 5.2.1.

Command is `fplll basis_file -a bkz -b 20`

<br>
<br>

## Experimental Table

| experiment | Machine           | Instance:<br /> (dimension, seeds) | Information sharing:<br />size of share-data pool | Heterogeneous algorithms:<br />(#DeepBKZ solvers, <br />#sub-ENUM solvers, <br />#GaussSieve solvers) |
| ---------- | ----------------- | --------------------------------- | ------------------------------------------------- | ------------------------------------------------------------ |
| 1          | CAL A, CAL B      | (130, 0-4)                        | 100000, 1, 0                                      | (143, 0, 0)                                                  |
| 2          | CAL A, CAL B      | (110, 0-4)                        | 100000                                            | (143, 0, 0), (126, 16, 1), <br />(110, 32, 1), (78, 64, 1)   |
| 3          | CAL A, CAL B      | (130, 0-4)                        | 100000                                            | (143, 0, 0), (126, 16, 1), <br />(110, 32, 1), (78, 64, 1)   |
| 4          | CAL A, CAL B      | (130, 0)                          | 100000                                            | (143, 0, 0)                                                  |
| 5          | CAL A, CAL B, ITO | (130, 0-4)                        | 100000                                            | (143, 0, 0), (2303, 0, 0)                                    |
| 6          | Emmy              | (130, 0)                          | 100000                                            | (12192, 0, 0)                                                |
| 7          | Emmy, Lisa        | (130, 0)                          | 100000                                            | (12192, 0, 0), (103584, 0, 0)                                |




