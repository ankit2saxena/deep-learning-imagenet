# deep-learning-imagenet
Comparison of different DL models used on ImageNet database.

#### 1. Create virtual environment for Python
    python -m venv deep-learning-imagenet-virtenv
   
#### 2. Activate virtual environment for Python
    deep-learning-imagenet-virtenv/Scripts/activate.bat
    
#### 3. Upgrade pip
    python -m pip install --upgrade pip
    
#### 4. Install required libraries
    pip install -r deep-learning-imagenet/requirements.txt
    
#### 5. Create a Jupyter notebook specific to deep-learning-imagenet-virtenv
    ipython kernel install --user --name=deep-learning-imagenet-virtenv
    
#### 6. Start Application
    python wsgi.py
    
#### 7. Deactivate virtual environment
    deactivate
    
#### 8. Visualization URL
    localhost 

### References
1. Dataset: https://patrykchrabaszcz.github.io/Imagenet32/
2. ImageNet labels: https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a
3. A Downsampled Variant of ImageNet as an Alternative to the CIFAR datasets (Patryk Chrabaszcz, Ilya Loshchilov & Frank Hutter, 2017)