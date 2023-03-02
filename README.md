## DSPS23_Competition
We took part in track 1, which utilized a data-centric methodology as opposed to the conventional model-centric strategy. In order to increase the accuracy of the model architecture, the competition's goal was to modify or enrich the dataset provided by utilizing any data cleaning, annotations, or augmentation.

Actions Taken:

The model was run over a range of epochs (100–300). The best outcomes came from 223 epochs. To obtain a better mAP, test-time augmentations were used during testing.

The accuracy of the model before test-time augmentation was 0.36. When test-time augmentation is used, a confidence of 0.4 and an intersection of union threshold of 0.99, the accuracy increases to 0.71.

Further experiments were conducted on the testing by altering the confidence. The accuracy results for the various confidence levels are presented in the table below.

![Screenshot from 2023-03-01 18-24-36](https://user-images.githubusercontent.com/93742592/222298132-b2ff7e4b-02ed-46fc-897f-18220f5f7c20.png)
