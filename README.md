# MERL Schema

This is the Matching Extension Ranking List (MERL) schema as first introduced by the publication "[dbling: Identifying
Extensions Installed on Encrypted Web Thin Clients](https://doi.org/10.1016/j.diin.2016.04.007)". As described more
fully in the paper, the purposes of a MERL file are to:
1. List (using their `inode` numbers) evidence [artifacts](http://forensicswiki.org/wiki/Artifacts) that have been
   evaluated to be potential root directories for installed extensions, and
2. List the extensions calculated to be the most likely matches for each of these artifacts.

Because they serve a similar purpose, this schema directly references and depends on the
[DFXML schema](https://github.com/dfxml-working-group/dfxml_schema).
