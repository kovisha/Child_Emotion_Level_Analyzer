####################################################################################################
EMOTION LEVEL ANALYZER

Backend management consists of:

1. Openface toolkit manipulation - MMSA FET
2. EFA based AU seperation.
3. AU based K means clustering.
4. Emotion level Machine learning algorithms based on Age  - KNN, SVM, RF 
5. Models trained with Age variation. (pkl files included - RF is the best model)
6. Classifier predicting codes to test a video.

# Execute Program with the following command

python main.py --mode video --input \Video\S1_happy_1.mp4 --age 1