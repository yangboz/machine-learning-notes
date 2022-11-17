# machine-learning-notes
Collection of useful machine learning codes and snippets (originally intended for my personal use)

## first off,install the nightly release for  The M1 GPU support 
```
 pip3 install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu 
```




MPS benchmark

```
python lenet-mnist.py --device "mps"
```

 97.77%
Time elapsed: 0.30 min
Total Training Time: 0.30 min
Test accuracy 97.40%
Total Time: 0.34 min
