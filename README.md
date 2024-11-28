## Dont not use the mentioned requirements file to install deps, instead install these
* diffuser - `pip install -U diffuser`
* pyTorch - `pip install torch`
* accelerate - `pip install accelerate`

First it will download models and its safetensors which are more 30 giga bit in size.
To save your computer from OutOfStorage error, add `HF_HOME = <drive>://path/to/custom/tempCache` in your users environment variables
Accelerate is a must otherwise your system will definitely hit 100% memory usage and crash your windows/application.

Need fix for - It throws cuda error for insufficient vram on a 8gb 3060ti GPU, W flux T-T
