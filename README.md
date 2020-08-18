# ***handwritten-digits-classification***
## Classification of handwritten digits using tensorflow + Feature Engineering.

The images in the rawTest and rawTrain folders are the material of this repository, jpg files inside folders belong to MNIST database.

## ***To run***
It's better to use jupyter notebook or jupyter lab. 
* To install the required packages insert a cell in jupyter and run the following code in it:
    ```
    import pip
    def install(package):
        if hasattr(pip, 'main'):
            pip.main(['install', package])
        else:
            pip._internal.main(['install', package])
    if __name__ == '__main__':
        install('pandas')
        install('numpy')
        install('opencv-python')
        install('scikit-learn')
        install('tensorflow')
        install('matplotlib')
    ```
    Or manually install 'pandas', 'numpy', 'opencv-python',     'scikit-learn', 'tensorflow', 'matplotlib'.

* In the next step, specify the path of the 'rawTest' and 'rawTrain' folders in the dataExtraction.ipynb file (test_src, train_src)

    In the same way, specify the path of the final 'Test' and 'Train' folders that you created yourself(test_dir, train_dir variables)
    A lot of data will be placed in this paths.
* Set the 'Train' and 'Test' paths in train_dir and test_dir variables in the trainModel.ipynb
* First run the cells in dataExtraction.ipynb and then trainModel.ipynb


<!-- ## ***Feature Engineering***
* [Find the digits of each image]()

* [Save digits in its corresponding folder]()

* [Make an array of digits (png files) and their labels]()

## ***Training Model***
* 
*
* -->
