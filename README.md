# Plant Health Classifier

This project is a deep learning model that identifies whether a plant is healthy or not by analyzing photos of its leaves. It's trained to classify plants into various categories based on their health status.

## Dataset

The model was trained on the PlantVillage dataset, which includes the following classes:

- Pepper__bell___Bacterial_spot
- Pepper__bell___healthy
- Potato___Early_blight
- Potato___Late_blight
- Potato___healthy
- Tomato_Bacterial_spot
- Tomato_Early_blight
- Tomato_Late_blight
- Tomato_Leaf_Mold
- Tomato_Septoria_leaf_spot
- Tomato_Spider_mites_Two_spotted_spider_mite
- Tomato__Target_Spot
- Tomato__Tomato_YellowLeaf__Curl_Virus
- Tomato__Tomato_mosaic_virus
- Tomato_healthy


## Dataset Link

```bash
https://www.kaggle.com/datasets/arjuntejaswi/plant-village
```


## How to Use

1. Clone this repository:

```bash
git clone https://github.com/biswadeep_roy/Plant-Health-Classifier.git
```


Install the required libraries:

```bash
pip install -r tensorflow
pip install matplotlib

```
Open the Jupyter Notebook (Plant_Health_Classifier.ipynb) to see the code and run the model.

Follow the instructions in the notebook to train or use the pre-trained model.

## Results

The model achieved an accuracy of 98.39% on the validation dataset.

## Project Structure
/data: Directory for data sources and preprocessing scripts.
/notebooks: Contains Jupyter Notebook for model development and evaluation.
/models: Model checkpoints and saved models.
/scripts: Additional Python scripts if necessary.

## Data Source and Preprocessing
To obtain the PlantVillage dataset, visit the data source. In the data directory, you can find preprocessing scripts and instructions to prepare the dataset for training.

## Hyperparameter Tuning
If hyperparameter tuning was performed, the best hyperparameters and the reasons for choosing them are documented in the Jupyter Notebook.


## Model Checkpoints
You can download pre-trained model checkpoints from the /models directory. Use these checkpoints for inference or further training.
## Error Handling
The code includes error handling and informative error messages for common issues users might encounter.

## Testing
To ensure that the code is working as expected, unit tests have been implemented. You can find them in the /tests directory.

## Citation
If you use existing research or datasets, provide proper citations in your work to give credit to the original authors and sources.

## Visualization
The Jupyter Notebook contains various visualizations, including sample predictions, training curves, and data analysis to help users understand the project better.

## Performance Comparison
Consider adding a section that compares your model's performance with other existing models or research in the field, providing users with context for your results.
 
## Model Deployment
It is a real-world application and can be deployed to GCD, AWS or any other cloud service

## Contributing

If you would like to contribute to this project, please fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License.

