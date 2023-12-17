# Flying a Drone Through a Hoop

Precision flight with drones in dynamic environments have potential in many fields. In this work, we develop a pipeline to fly a quadcopter through a swinging pendulum in simulation, a simpler model of these types of dynamic settings. 

# Code Setup and Run

This code is in the form of a .ipynb and can be run using any service that supports running a Jupter notebook.

## Using Jupyter Notebook

1. **First, install jupyter:**
```bash
  pip install jupyter
```
2. **Navigate to the Directory:**
Open a terminal or command prompt and navigate to the directory where your .ipynb file is located.

3. **Run Jupyter Notebook:**
Type the following command and press Enter. This will open a new tab in your web browser with the Jupyter Notebook interface.
```bash
jupyter notebook
```
4. **Open and run the notebook:**
   In the Jupyter Notebook interface, navigate to the .ipynb file and click on it to open it.
Use the toolbar to run cells individually or use the "Run All" option to execute all cells in the notebook.

# Dependency Installation Instructions

This code requires several Python libraries and packages to run successfully. Below are the necessary installations for the imports used in the code:

1. **Math and Image Processing:**
    ```bash
    pip install numpy matplotlib mpld3 opencv-python
    ```

2. **Drake and Underactuated Packages:**
    ```bash
    pip install pydrake underactuated
    ```

3. **PyTorch and torchvision:**
    ```bash
    pip install torch torchvision
    ```

4. **Meshcat Visualizer:**
    ```bash
    pip install meshcat
    ```

5. **Miscellaneous:**
    ```bash
    pip install dataclasses torch
    ```

**Note:**
    - The `underactuated` package might need additional dependencies. Please refer to the official documentation if any issues arise: [Underactuated - Drake](https://github.com/RussTedrake/underactuated)

8. **Drake Visualizer Setup:**
   - The code uses Meshcat for visualization. Make sure to have Meshcat server running. If not installed, install it using:
      ```bash
      pip install meshcat
      ```

9. **Meshcat Configuration:**
    - If you're facing issues with Meshcat, refer to the official documentation for troubleshooting: [Meshcat - Drake](https://github.com/RussTedrake/meshcat-python)

**Additional Notes:**
    - The code is developed and tested with specific versions of the mentioned libraries. If you encounter any issues, consider checking the compatibility with your installed versions.
    - The `mpld3.enable_notebook()` line is specific to Jupyter Notebooks. If you're using a different environment, you might need to adjust this part.
