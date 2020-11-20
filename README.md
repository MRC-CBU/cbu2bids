# DEPRECATED
This method for accessing dcm2bids is no longer supported. Please access dcm2bids
through [neuroconda](https://github.com/jooh/neuroconda) instead.

# cbu2bids
DICOM to BIDS conversion for MRC CBU (using Johan Carlin's fork of
[dcm2bids](https://github.com/jooh/Dcm2Bids)).

This shell script takes care of setting your system path so that everything
works out of the box (if you're on the CBU imaging system). It can be called
with the exact same call syntax as dcm2bids (with the exception that that the -a
flag is being set for you automatically).

An example config file that has been used to share CBU data on openfmri (see
[this repo](https://github.com/jooh/facedistid_analysis)) can be found under
[examples](examples).

# Getting started

Just do something like `set path = ( $path /imaging/local/software/cbu2bids )`
to get the shell script on your system path. Confirm that everything works with
`cbu2bids -h -o test`. If you get a nice help prompt, you are up and running.

# Problems, concerns, queries?
Open an issue, or contact Johan Carlin.
