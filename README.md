
# Image Captioning

Automatically generating text descriptions for images using computer vision and natural language processing.

Download COCOAPI tools and paste it in a folder named opt inside the project folder https://github.com/cocodataset/cocoapi .

Update the location of the files in each python file before execution.

## Training
Download the Training Images and paste it in opt/cocoapi/images http://images.cocodataset.org/zips/train2017.zip .

Download the Training annotations and paste it in opt/cocoapi/annotations http://images.cocodataset.org/annotations/annotations_trainval2017.zip
## Validation
1. Download the Validation Images and paste it in opt/cocoapi/images http://images.cocodataset.org/zips/val2017.zip .

2. Run the Validation-final.ipynb to generate captions_val2017_results.json file.

3. Download pycoco eval api folder from ms coco github https://github.com/tylin/coco-caption run

```bash
  chmod +x get_stanford_models.sh
```
and

```bash
  ./get_stanford_models.sh
```
make sure java is installed in the downloaded folder.

4. Copy captions_val2017.json file from dataset folder and paste it in annotations folder copy captions_val2017_results.json file generated to results folder.

5. Copy validationresults.ipynb to downloaded folder from github and run it.
## Testing
Download the Test Images and paste it in opt/cocoapi/images http://images.cocodataset.org/zips/test2017.zip
## For user input testing
Download COCOAPI, modify the locations in the required python files and run the testing-final.ipynb . It will use the pretrained model uploaded in the github and ask the user for the location of the image.
