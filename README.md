# SC4000-Leaf-Project

cassava leaf classification project

## Steps for Kaggle Dataset API
1. pip install kaggle
2. Copy the kaggle.json file in this directory
3. Paste it into
    ```
    C:\Users\<Your-Username>\.kaggle\kaggle.json (windows)
    ```
    ```
    ~/.kaggle/kaggle.json (mac)
    ```

4. Ensure file has correct permissions
    ```
    chmod 600 ~/.kaggle/kaggle.json
    ```

5. Run the kaggle comps download cell
6. Unzip the file either in file explorer or through the unzip cell
  - DOUBLE CHECK YOUR DIRECTORY

## Libraries needed
```
pip install os-sys
pip install regex
pip install DateTime
pip install numpy (make sure latest version)
    - pip install --upgrade numpy
pip install pandas
pip install matplotlib
pip install tensorflow (make sure latest version)
pip install zipfile36
pip install scikit-learn
pip install torchvision
```

## Reference Material for Models
[Dense Net 169](https://pytorch.org/vision/main/models/generated/torchvision.models.densenet169.html#torchvision.models.densenet169)

[CropNet](https://www.tensorflow.org/hub/tutorials/cropnet_cassava)
