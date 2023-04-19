# Image-to-Prompt Model
This is the repository for Interdisciplinary Data Science 705: Principles of Machine Learning final project. 

## Purpose Of Project
This study explores the possibility of reversing the relationship between text and image using advanced Vision-Language Pre-training (VLP) frameworks, such as the BLIP and ViT models. We examined a dataset of 7,000 images, randomly selected from DiffusionDB, which features a wide range of prompt-image associations. By leveraging transfer learning and pre-training techniques, we fine-tuned the models and assessed their performance using cosine similarity as the evaluation metric. Our findings demonstrate that the fine-tuned BLIP model significantly surpasses the zero-shot baseline, showing a 25% improvement in average cosine similarity scores on the test set. While the model effectively describes image content, it faces challenges in understanding context, object relationships, and interpreting idioms or metaphors. We also acknowledge the limitations of cosine similarity as an evaluation metric, as it does not consider the sensibility of phrases. Future research should investigate alternative metrics and additional fine-tuning methods to enhance performance on complex and abstract image-text relationships.

## How To Run / Train Models

**Step 1 - Install Required Libraries**
```
pip install -r requirements.txt
```

**Step 2a - Run BLIP Model**
All necessary code used to train the BLIP model are found under `02_code/BLIP_training.ipynb`.

