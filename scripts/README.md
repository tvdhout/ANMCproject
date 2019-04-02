This folder contains the scripts used in this project.

[segment songs](https://github.com/tvdhout/ANMCproject/blob/master/scripts/Segment%20songs.ipynb) takes the raw audio files and splits them into chorus and verse segments from which the features are extracted in a later stage.

[Feature Extraction](https://github.com/tvdhout/ANMCproject/blob/master/scripts/Feature%20Extraction.ipynb) takes the audio segments (choruses and verses) and extracts the features described in the [report](https://github.com/tvdhout/ANMCproject/blob/master/Report.pdf).

[Classification with comparison](https://github.com/tvdhout/ANMCproject/blob/master/scripts/Classification%20with%20comparison.ipynb) takes the feature vectors extracted in the previous notebook and classifies chorus and verse with comparison, analogous to human experiment 1.

[Classification no comparison](https://github.com/tvdhout/ANMCproject/blob/master/scripts/Classification%20no%20comparison.ipynb) takes the feature vectors extracted in the Feature Extraction notebook and classifies chorus and verse without reference to the sample's counterpart, analogous to human experiment 2.
