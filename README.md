Download COCOAPI tools and paste it in a folder named opt inside the project folder 
https://github.com/cocodataset/cocoapi

Update the location of the files in each python file before execution

TRAINING
Download the Training Images and paste it in opt/cocoapi/images
http://images.cocodataset.org/zips/train2017.zip
Download the Training annotations and paste it in opt/cocoapi/annotations
http://images.cocodataset.org/annotations/annotations_trainval2017.zip



VALIDATION 
Download the Validation Images and paste it in opt/cocoapi/images
http://images.cocodataset.org/zips/val2017.zip

run the Validation-final.ipynb to generate captions_val2017_results.json file
download pycoco eval api folder from ms coco github https://github.com/tylin/coco-caption
run chmod +x get_stanford_models.sh and ./get_stanford_models.sh
make sure java is installed
In the downloaded folder-
copy captions_val2017.json file from dataset folder and paste it in annotations folder
copy captions_val2017_results.json file generated to results folder
copy validationresults.ipynb to downloaded folder from github and run it

TESTING
Download the Test Images and paste it in opt/cocoapi/images
http://images.cocodataset.org/zips/test2017.zip

Download the test image info and paste it in opt/cocoapi/annotations
http://images.cocodataset.org/annotations/image_info_test2017.zip


FOR USER INPUT Testing
Download COCOAPI, modify the locations in the required python files and run the testing-final.ipynb . It will use the pretrained model uploaded in the github and ask the user for the location of the image.

