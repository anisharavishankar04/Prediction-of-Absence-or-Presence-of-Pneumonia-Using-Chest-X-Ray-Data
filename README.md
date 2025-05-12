# Prediction-of-Absence-or-Presence-of-Pneumonia-Using-Chest-X-Ray-Data

This project uses a pre-trained CNN model, MobileNetV2, to classify images and predict the absence or presence of pneumonia. The dataset is available on Kaggle and has been linked below. 

## Task
This is a binary classification task, where the model obtained a test accuracy of **84.62%**.

## Dataset
The dataset used in this project is available on Kaggle. You can find it [here](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

## Usage Instructions

1. Clone the repository using the following command:
    ```bash
    git clone https://github.com/anisharavishankar04/Prediction-of-Absence-or-Presence-of-Pneumonia-Using-Chest-X-Ray-Data.git
    ```

2. Open Google Colab on your browser and sign in.

3. If the pop-up doesn't automatically show up, go to **File -> Open notebook -> Upload**. Either browse and add the `.ipynb` file or simply drag it onto the screen. The notebook will open in Google Colab.

4. Upload the dataset onto your Google Drive.

5. Go back to your Colab notebook and change the runtime type to **T4 GPU**:
    - **Runtime -> Change runtime type -> T4 GPU**

6. In the Colab notebook, go to **Runtime -> Run All** to run the entire notebook.

7. You will be prompted to connect your Google Drive when the corresponding cell runs.

8. Run the rest of the cells, and that completes the execution.

## Results
The model achieved a test accuracy of **84.62%** on the classification task.

## Acknowledgments
- Dataset: [Kaggle - Pneumonia Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- MobileNetV2 pre-trained model
- Google Colab for running the notebook with GPU support
