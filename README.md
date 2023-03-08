OBJECT DETECTION \_ Lorenzo Venieri

The source code can be found in the notebook: “Cars\_Detection.ipynb”

The project was developed on Google Colab. 

To ease the data preparation I’ve moved the “annotations\_sample.json” file out of the “car” folder

The output with the car boxes in (Cx,Cy,W,H) format is in the file: “car\_bboxes\_RightFormat.csv”

The output in format (x1,y1,x2,y2) is in the file: “car\_bounding\_boxes.csv” , I’ve used it in the notebook because this format is easier to work with when using Detectron2.

The bounding boxes of the cars detected as red is in the file “red\_cars\_bboxes.csv”, boxes are in XYXY\_ABS format.

To train and validate the model using Detectron2 it was useful to generate two json files “cars\_annotations\_train.json” and “cars\_annotations\_val.json” with the annotations for the images in COCO format.


