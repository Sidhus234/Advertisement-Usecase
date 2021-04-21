## Description
A television channel company/organisation makes money from advertisement. An interesting area for ML use-case would be to look for moments of their programming that might be of commercial interest. For example, if the program the viewer is watching contains scenes of someone drinking a hot beverage, that might be a particularly good opportunity to show an ad for coffee.Whiskey contextual image appears in Homeland at 8 mins 46 seconds, thus the next ad-break at 11 minutes show a whiskey ad by Haig Club (Hypothetical Scenario)

Provided is a dataset (in //Data folder) where they applied a 3rd party object recognition model to images, they extracted from some of their TV shows at 1-second intervals. Essentially, they took a screenshot every second and fed it to AWS Recognition, which outputs continuous “confidence scores” between 0-1 for over a thousand pre-defined object and scene types

## Data
Due to size limits of uploading file in Github, the actual data is broken down in three parts (part_01, part_02 and part_03). Have added a simple jupyter notebook (in //Codes// folder) to append the files to one another to run the other codes
