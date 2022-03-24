# eff_v0.1
Team F Algovera-Lynx hackathon to process EEG data.

An early decision we made was to directly download data from OpenNeuro, bypassing Ocean. We were able to dowload data as needed to a local machine and plot raw traces using MNE-bids and plot them in MNE-Python, filter them and do some preliminary processing including making power spectra.
Our main code is the file labelled 'EEG_classifier.ipynb'. The current accuracy is 0.2.
