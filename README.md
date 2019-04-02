# CBIR

### Description
This project builds a personal image search engine. It returns similar images based on the query image. It analyzes the contents of the image rather than the metadata such as keywords, tags, or descriptions associated with the image for searching. I have used color based histogram to find the similarity between images.



## Requirement
1. Python3
2. OpenCV 3.0 and above
3. numpy
4. Dataset(http://lear.inrialpes.fr/people/jegou/data.php) -> converted into PNG 

## RUN
1. $ workon cv
2. $ python search.py --index index.csv --query queries/127502.png --result-path dataset
