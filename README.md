# Face-Mesh

Machine Learning Model to detect the Face, Iris and Pose of the person.

Technology: OpenCV and Numpy, Training script uses SVM Model.

## Execution
Simply download and install the app and naviagte within the files to get the app running.\
You can press 'q' key to quit the app.

- Now you may execute **Face_Mesh.py** to see this app in action for face mesh detection.
- You may execute **Iris_Detection.py** to for iris detection.
- You may execute **Pose_Detection.py** to for pose detection.

## Installation
The app's installation process is quite easy. Simply clone this github repo from your terminal or press download as zip, 
and then unzip the downloaded folder to the directory of your choice.

Then navigate to the the directory and inside the folder open your terminal and type:
```
pip install -r requirements.txt
```

You can even install this app inside a virtual environment go on and create a virtual environment (explained below) and 
then follow the same steps as explained in this section.


## Creating a Virtual Environment:
- Make sure you have `python-pip` installed, and download **virtualenv**:
  ```
  pip install virtualenv
  ```
- Then create a virtual environment (you can give any name in place of 'venv'), copy and paste the code in your terminal:
  ```
  virtualenv venv
  ```
- Now activate this virtual environment
  - On Mac OS/Linux:
    ```
    source venv/bin/activate
    ```
  - On Windows:
    ```
    venv\Scripts\activate
    ```

