# ConvBonsai Tree


Its a recent research by Microsoft Research India on non linear decision tree based method for classification purpose. It achieves high accuracy with less size for resource constraint devices. I am reproducing the code with a bit of simplification.


Link to Bonsai Model research done by Microsoft Research India : https://github.com/Microsoft/EdgeML

Modified the current bonsai model to include convolutional layers which further decreases the model size increases CNNs explainability and increamental learning can be done. 

Link to Comparison of different other models and report by our group on this model : https://github.com/yadavdeepak95/Pocket-ML


A recent Publication following this method is : https://arxiv.org/pdf/1904.08249.pdf



## Usage 

It's by default set to use cifar 10 dataset.

Run

```
python ./main.py
```
