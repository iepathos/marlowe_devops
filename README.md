# Project Marlowe

Project Marlowe is an open source web service and accompanying extensions and applications for determining the objectivity of text.

# Components

+ objectivity uses Python TextBlob to estimate an objectivity score from a NaiveBayes network trained on movie reviews.

+ usent classifies subjectivity using polarity lexicons [github.com/nik0spapp/usent](https://github.com/nik0spapp/usent) trained on an array of sources.

+ chrome is the Google Chrome extension built for Marlowe.

+ blog contains blog posts for the building and development of Project Marlowe.

# Dev Setup

````shell
git clone https://github.com/iepathos/marlowe_devops
cd marlowe_devops
git submodule update
````
