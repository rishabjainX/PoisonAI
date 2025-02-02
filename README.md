# 🌿 PoisonAI
An Image Classification Model trained on 6000+ images of various plants. When an image is uploaded, it returns whether the plant is poisonous or not. The website for our software is available here: https://poisonai.my.canva.site/

<img width="658" alt="Screenshot 2023-07-09 at 11 08 15 AM" src="https://github.com/rishabjainX/PoisonAI/assets/86537371/6c457dfd-e172-4a72-bdf1-389bf85b22eb">

To use, see the "PoisonAI.ipynb" file. Run all the cells, and go to this website: https://poison-ai.anvil.app

<img width="522" alt="Screenshot 2023-07-09 at 11 08 33 AM" src="https://github.com/rishabjainX/PoisonAI/assets/86537371/800057d3-1939-4056-8112-71ca14088a32">

Follow the directions:
1) Click the "upload" button.
2) Choose an image of a plant from your files.
3) Click open. Wait a few seconds and the model should return a result!
   
<img width="1148" alt="Screenshot 2023-07-09 at 11 12 09 AM" src="https://github.com/rishabjainX/PoisonAI/assets/86537371/a7236651-9ccf-4a75-9671-6446a3caeb9c">

This model is not super accurate. It varies from around 60-80% accuracy. Unfortunately, we did not have enough time to improve the accuracy of the model or include additional features such as validation data. In the future, we also wanted to create an iOS application that can implement this model.

The dataset we used can be found on Kaggle: https://www.kaggle.com/datasets/sandramai/poisonous-plants

We modified it slightly to remove the categories. We merged all the poisonous plants (oak, ivy, and sumac) into one folder.
