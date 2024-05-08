# Hindi-Characters-Restoration-using-Image-Inpainting
A dual-stage model integrating a custom EfficientNet model and a Deep Image Prior (DIP) model for inpainting the missing regions in deteriorated hindi documents.

# Inpainting with DIP and Efficientnet

## Training the Model

- The notebook begins with loading the dataset and setting up the necessary environment for training.
- The EfficientNet-B0 model is used and modified for the specific number of classes in the dataset.
- Data transformations and DataLoader are defined to preprocess the dataset.
- The model is trained using the defined loss function and optimizer for a specified number of epochs.
- The trained model is saved for later use.

## Inpainting Process

- The notebook imports the trained model and sets up the DIP library for inpainting.
- Image and mask selection and visualization are performed.
- The main loop for inpainting is executed, which involves setting up the neural network, defining parameters, and optimizing the model.
- The loss curve over iterations is plotted to visualize the training progress.
- The inpainted image is generated and displayed.

The notebook provides a comprehensive overview of the inpainting process using DIP and EfficientNet for Hindi characters.

For detailed implementation and code execution, refer to the provided Colab notebook.
