# PoisonAI
An Image Classification Model trained on 6000+ images of various plants. When an image is uploaded, it returns whether the plant is poisonous or not.

To use, see the attached Jupyter Notebook file. Run all the cells, and go to this website: https://poison-ai.anvil.app

Follow the directions:
1) Click the "upload" button.
2) Choose an image of a plant from your files.
3) Click open. Wait a few seconds and the model should return a result!

This model is not super accurate. It varies from around 60-80% accuracy. Unfortunately, we did not have enough time to improve the accuracy of the model or include additional features such as validation data. In the future, we also wanted to create an iOS application that can implement this model.

The dataset we used can be found on Kaggle: https://www.kaggle.com/datasets/sandramai/poisonous-plants

We modified it slightly to remove the categories. We merged all the poisonous plants (oak, ivy, and sumac) into one folder.
