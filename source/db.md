### Substructure searches

Example query molecules taken from the [eMolecules home page](http://www.emolecules.com/):

    chembl_25=# select count(*) from rdk.mols where m@>'c1cccc2c1nncc2' ;
     count
    -------
       461
    (1 row)
    
    Time: 107.602 ms
    chembl_25=# select count(*) from rdk.mols where m@>'c1ccnc2c1nccn2' ;
     count
    -------
      1124
    (1 row)
    
    Time: 216.222 ms

