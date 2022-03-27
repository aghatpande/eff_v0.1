# eff_v0.1

Team F Algovera-Lynx hackathon to process EEG data.

An early decision we made was to directly download data from OpenNeuro, bypassing Ocean. We were able to dowload data as needed to a local machine and plot raw traces using MNE-bids and plot them in MNE-Python, filter them and do some preliminary processing including making power spectra.
Finally, we used the training data provided by the organizers to create the classifier.
Our main code is the file labelled 'EEG_classifier3.ipynb'. The current accuracy is 0.2.
