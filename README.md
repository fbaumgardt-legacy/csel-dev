csel-dev
========

Corpus Scriptorum Ecclesiasticorum Latinorum: a machine-corrected EpiDoc version of public domain volumes of the monumental collection of Latin Church Fathers. 

Each volume is encoded in accordance with the latest EpiDoc standards (CTS-compliant). Each XML file contains a link to the Archive.org scan the text was taken from as well as Perseus Catalog URIs (where available). 

This is the split-file version, where the textpart leaf elements have been moved to individual files. This is meant to simplify the process of making every segment of every work CTS-addressable as well as converting to a BSON format and importing to MongoDB. The code for conversion can be found in https://github.com/fbaumgardt/perseus-citology (currently not public).

A list of CSEL volumes and contents can be accessed here: http://www.csel.eu/?id=19
