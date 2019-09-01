# Google--Open-Image 
# Deadline--10/01/19

## Time Table
* 08/15/19 THU--08/17/19 SAT  

  learn python and "Yolo" 

## Dependencies

Python3, tensorflow, numpy, opencv, YOLO v3.

### Getting started

You can choose _one_ of the following three ways to get started with darkflow.

1. Just build the Cython extensions in place. 
NOTE: If installing this way you will have to use `./flow` in the cloned darkflow directory instead of `flow` as darkflow is not installed globally.
    ```
    python3 setup.py build_ext --inplace
    ```

2. Let pip install darkflow globally in dev mode (still globally accessible, but changes to the code immediately take effect)
    ```
    pip install -e .
    ```

3. Install with pip globally
    ```
    pip install .
