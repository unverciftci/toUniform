# A simple neural model for unlabelled data

This model transforms data to uniformly distributued points. This is achived just by mapping nearby points to distants images. By doing this tranformation, it is easy to understand the structure behind the data and even generate new data. Details can be found in our preprint which is under review and will be released soon. 


<img src="https://github.com/unverciftci/toUniform/blob/main/images/flow.png" alt="Alt text" title="Optional title">

For demonstration we transform dataset onto a plane so that the underlying pattern behind the data is visible. Just give try! 

First one is Swis Roll dataset shown in fugures below and the implementation is here: https://github.com/unverciftci/toUniform/blob/main/DatatoUniformSR.ipynb.

<img src="https://github.com/unverciftci/toUniform/blob/main/images/sr3.png" alt="Alt text" title="Optional title">
<img src="https://github.com/unverciftci/toUniform/blob/main/images/sr2.png" alt="Alt text" title="Optional title">


Second example is MNIST dataset shown in fugures below and the implementation is here: 
https://github.com/unverciftci/toUniform/blob/main/DataToUniformMnist.ipynb

<img src="https://github.com/unverciftci/toUniform/blob/main/images/mnist1.png" alt="Alt text" title="Optional title">
<img src="https://github.com/unverciftci/toUniform/blob/main/images/mnist.png" alt="Alt text" title="Optional title">


```{r, figures-side, fig.show="hold", out.width="50%"}
par(mar = c(4, 4, .1, .1))
<img src="https://github.com/unverciftci/toUniform/blob/main/images/sr3.png" alt="Alt text" title="Optional title">
<img src="https://github.com/unverciftci/toUniform/blob/main/images/sr2.png" alt="Alt text" title="Optional title">
```
