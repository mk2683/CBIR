# CBIR

### Description
Thiis project builds a personal image search engine. Given our dataset of vacation photos, we want to make this dataset “search-able” by creating a “more like this” functionality — this will be a “search by example” image search engine. For instance, if I submit a photo of sail boats gliding across a river, our image search engine should be able to find and retrieve our vacation photos of when we toured the marina and docks.



## Requirement
1. Python3
2. OpenCV 3.0 and above
3. numpy
4. Dataset(http://lear.inrialpes.fr/people/jegou/data.php) -> converted into PNG 

## RUN
1. $ workon cv
2. $ python search.py --index index.csv --query queries/127502.png --result-path dataset
