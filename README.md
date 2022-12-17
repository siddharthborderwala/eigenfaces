# eigenfaces project

In this project I have used the concepts of Eigen Vectors to perform Principal Components Analysis and Dimensionality Reduction on images for improving performance of face recognition algorithms.

One of the main benefits of using PCA for face recognition is that it can reduce the dimensionality of the data, which makes it easier to process and analyze. For example, if you have a dataset of face images that are represented as large matrices of pixel values, PCA can be used to find a smaller set of features that capture the most important information about the faces. These features can then be used as input to a machine learning algorithm, such as a support vector machine (SVM), to classify the faces.

In summary, PCA can be useful for face recognition because it can help to extract important features from face images, reduce the dimensionality of the data, and improve the performance of machine learning algorithms.

# execution

I have used python language and jupyter notebooks to carry out the demonstration.

## how to run the code

1. Clone this repository

```bash
git clone https://github.com/siddharthborderwala/eigenfaces.git
```

2. Create a python virtual environment

```bash
# enter the project directory
cd eigenfaces

# initialize the virtual env - will create a new .env directory in the project folder
python3 -m venev .env/
```

For more help with this, you can refer to the official documentation site of python [here](https://docs.python.org/3/library/venv.html)

3. Install required packages

The [requirements.txt](./requirements.txt) file contains the auto generated list of packages used in the project.

```bash
.env/bin/python3 -m pip install -r requirements.txt
```

4. Open Jupyter Notebook

```bash
# starts the jupyter server
.env/bin/jupyter notebook
```

Go to `http://localhost:8888/tree` and open `notebook.ipynb` to view the code

> Note: Follow each of these steps carefully and correctly to run the code with ease
