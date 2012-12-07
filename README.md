spatial_feature_selection
========================

This project contains the data used for our research paper about feature selection for spatially relevant features. In order to be able to reproduce the results from the Wikipedia evaluation carried out in the paper, we here provide the testfile we used.

The contents of this project are:
* features.txt - A sorted list of 301 968 features used in the paper
* testfile.orig.tar.gz - A compressed version of the original Wikipedia test data
* testfile.actual.tar.gz - A compressed version of the actual testfile used in the paper. This file contains the original Wikipedia test documents, matched to the set of features from Flickr we provide here. To this end, Flickr tags were matched for up to three consecutive words in the original text, e.g. the original test data ```buckingham palace road``` will be converted to  ```buckingham buckinghampalace buckinghampalaceroad palace road```.

### Features

The features in the list we publish, are gathered from a sample of 9.4 million geotagged Flickr photos. After extracting features that were used by at least 3 different users, we ended up with these 301 968 features. 

### Test set

The testfile contains 21 839 Wikipedia documents annotated with geographical coordinates that are located within a bounding box of the United Kingdom. This set of documents was constructed to contain only entities that can be considered as a certain location or spot.

### Questions

In case you have any questions, feel free to contact me.
