## Event Localization Corpus

This is the corpus for learning the locations of events described by sentences. It was created by me, Chris Ward, for my Master's Thesis in Computational Linguistics. The code for processing and and training on the corpus can be found [here](https://github.com/cmward/text-scene).

The corpus was built by annotating a subset of the Flickr30k images and transfering the image labels to the corresponding captions. Here, we only supply the image file and the ELC labels.

The corpus is contained in a single CSV file, where each row contains the fields:

    image_url: the picture in Flickr30k to which the label applies
    q1: answer to the question 'Is the location in the image indoors or outdoors?'
    q2: answer to the question 'Is the location in the image man-made or natural?'
    q3: answer to the question 'If man-made, what is the function or type of the location in the image?'
    q4: answer to the question 'If natural, what type of natural location is it?'

