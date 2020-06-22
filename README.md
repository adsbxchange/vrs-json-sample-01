needs assembled

created with 

split -b 15M --numeric-suffix --suffix-length 4 csv-11-29-2020_sample.tar.bz2 "csv-11-29-2020_part_"

combine with

cat csv-11-29-2020_part_* > csv-11-29-2020_sample.tar.bz2
