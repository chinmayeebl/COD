# COD

The code (train.ipynb) trains a YOLOv8 object detection model on a Roboflow dataset, specifying training parameters. It evaluates the model's performance with a confusion matrix, results summary, and a prediction image. The trained model is then used for validation set detection, and predictions are saved. The best-performing model, represented by "best.pt," is provided in the link for deployment.

The YOLOv8 model is used for initial object detection and extract bounding box coordinates. The CamShift algorithm is used to establish and maintain tracking of the detected objects across frames, presenting the results in real-time visualization (tracker2.py).  This model is designed to perform well in challenging conditions, especially when targets are partially hidden, ensuring reliable results in real-world operational settings.

## Tailored for Camouflage Conditions:
Our system is designed with a primary focus on addressing camouflage challenges in military scenarios. It is finely tuned to detect targets even in intricate camouflage conditions, providing enhanced capabilities for military operations.

### Explore the Camouflage Dataset:
For detailed insights into our manual dataset creation and its integration into the model, please refer to our Camouflage Dataset (https://universe.roboflow.com/sih-clucx/camoflauge-object-detction). This dataset serves as a crucial foundation for training and fine-tuning the model.

### cite us:
@misc{
                            camoflauge-object-detction_dataset,
                            title = { Camoflauge Object Detction Dataset },
                            type = { Open Source Dataset },
                            author = { SIH },
                            howpublished = { \url{ https://universe.roboflow.com/sih-clucx/camoflauge-object-detction } },
                            url = { https://universe.roboflow.com/sih-clucx/camoflauge-object-detction },
                            journal = { Roboflow Universe },
                            publisher = { Roboflow },
                            year = { 2023 },
                            month = { sep },
                            note = { visited on 2024-02-19 },
                            }
