# BoundaryUNet
BoundaryUNet is a highly efficient and accurate method for estimating propagation pathloss from a boundary vector to all points on a 2D plane in realistic propagation environments with buildings. Unlike traditional methods, this framework does not require knowledge of the source location. The model uses a boundary vector and a map as inputs to estimate the pathloss in a given area without the presence of a source. 

For more information see the paper [UNet-Based Deep Learning Pathloss Estimator with Boundary Condition Input](https://link.pdf) (link will be available in early 2025).



## Usage Examples

Download and extract the [modified RadioMapSeer dataset](https://drive.google.com/file/d/1I19xK5nPC6H7XolefNrK-_WQgOS44Xlh/view?usp=sharing) to the folder of the Jupyter Notebook.

For training, see [BoundaryUNet_training.ipynb](/BoundaryUNet_training.ipynb).

For a test example, see [BoundaryUNet_test_example.ipynb](/BoundaryUNet_test_example.ipynb).
