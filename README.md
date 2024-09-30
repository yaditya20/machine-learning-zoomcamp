# machine-learning-zoomcamp
Homework and Notes for @DataTalkClub's ML Zoomcamp

## Setting up the Environment

Following are the steps to set up the environment using [Anaconda](https://www.anaconda.com/products/individual):

1. In terminal, run the following command to create the environment:
    ```
    conda create -n ml-zoomcamp python=3.11
    ```

2. Activate it using the following command:
    ```
    conda activate ml-zoomcamp
    ```

3. Install the following libraries - NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn, Jupyter notebooks:
    ```
    conda install numpy pandas scikit-learn seaborn jupyter
    ```

4. [Optional Step] Save the package info in requirements.txt file using the following commands:
    ```
    conda install pip

    pip list --format=freeze > requirements.txt
    ```
