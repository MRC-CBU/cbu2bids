# cbu2bids
DICOM to BIDS conversion for MRC CBU (using Johan Carlin's fork of
[dcm2bids](https://github.com/jooh/Dcm2Bids)).

This shell script takes care of setting your system path so that everything
works out of the box (if you're on the CBU imaging system). It can be called
with the exact same call syntax as dcm2bids (with the exception that that the -a
flag is being set for you automatically).

An example config file that has been used to share CBU data on openfmri (see
[this repo](https://github.com/jooh/facedistid_analysis)) can be found under
(examples)[examples].

# Problems, concerns, queries?
Open an issue, or contact Johan Carlin.
