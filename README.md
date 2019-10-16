# aromatics
Aromatic clusters in proteins

# To import database with Mysql
> cat aromatics.sql.gz.part-* > aromatics.sql.gz && zcat aromatics.sql.gz | mysql <Database name>

# To search for interactions
> ./Aromatics -i \<pdbfile\>

# To search for clusters
> ./Aromatics -i \<pdbfile\> -C

# To search only aromatic interactions with drugs
> ./Aromatics -i \<pdbfile\> -D

# To search only protein-protein aromatic interactions
> ./Aromatics -i \<pdbfile\> -P
