# Facial Expression Recognition

This webapp recognizes facial expressions using a custom Tensorflow.js model. The model trained using selected parts of the FER2013 dataset. It utilizes machine learning techniques to analyze facial expressions and classify them into different emotional categories and even occasionnaly plays some funny sounds! lol

See it here: <https://jwt2706.github.io/ExpressionRecognition/>

NOTE: The model isn't the best and isn't the most accurate, as this was more of a proof-of-concept and a learning oppertunity for myself. I would like to revisit this project to rework the model once I have time. This started out as a joke, but it actually got me interested. :D

## Emotional expressions

- Anger
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Suprise

## Run it locally
- `git clone https://github.com/jwt2706/ExpressionRecognition.git`
- `cd ExpressionRecognition`
- `npm i`
- `npm run dev`
- Open the `localhost` link in your browser
- There you have it! :)

## Dataset

The FER2013 dataset is used for training the facial expression recognition model. The dataset consists of images labeled with one of seven emotions: anger, disgust, fear, happiness, sadness, surprise, and neutral. However, only about 500 images of the dataset were used to train the model to speed the training process up.

## Model Training

If you want to train the facial expression recognition model using the FER2013 dataset, follow these steps:

1. Download the FER2013 dataset from [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data).

2. Preprocess the dataset to extract the selected parts you want to use for training.

3. Split the dataset into training and validation sets.

4. Train the model using the preprocessed dataset. You can use any machine learning framework or library of your choice.

5. Save the trained model weights and update the app to use the new model.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The FER2013 dataset: [https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)
