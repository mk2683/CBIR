# CBIR

### Description
This project builds a personal image search engine. Example:- Given a dataset of vacation photos, we can make it “search-able” by creating a “more like this” functionality — this will be a “search by example” image search engine. For instance, if I submit a photo of sail boats gliding across a river, this image search engine will be able to find and retrieve all the vacation photos which includes sail boats and river.



## Requirement
1. Python3
2. OpenCV 3.0 and above
3. numpy
4. Dataset(http://lear.inrialpes.fr/people/jegou/data.php) -> converted into PNG 

## RUN
1. $ workon cv
2. $ python search.py --index index.csv --query queries/127502.png --result-path dataset
