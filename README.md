# en-601-682-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [EN.601.682 Homework 2 Solved](https://www.ankitcodinghub.com/product/en-601-682-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94965&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;6&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (6 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EN.601.682 Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (6 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
1. The goal of this problem is to minimize a function given a certain input using gradient descent by breaking down the overall function into smaller components via a computation graph. The function is defined as:

f(x1,x2,w1,w2)= 1 +0.5(w12 +w2). 1 + e−(w1x1+w2x2)

(a) Please calculate ∂f , ∂f , ∂f , ∂f .

Solution:

</div>
</div>
<div class="layoutArea">
<div class="column">
∂w1 ∂w2

</div>
<div class="column">
∂x1 ∂x2

</div>
</div>
<div class="layoutArea">
<div class="column">
∂f x1 · e−(w1x1+w2x2)

∂w = (1 + e−(w1x1+w2x2))2 + w1

</div>
</div>
<div class="layoutArea">
<div class="column">
1

∂f x2 · e−(w1x1+w2x2)

</div>
</div>
<div class="layoutArea">
<div class="column">
∂w = (1 + e−(w1x1+w2x2))2 + w2 2

</div>
</div>
<div class="layoutArea">
<div class="column">
∂f = ∂x1

∂f = ∂x2

</div>
<div class="column">
w1 · e−(w1x1+w2x2) (1 + e−(w1x1+w2x2))2 w2 · e−(w1x1+w2x2) (1 + e−(w1x1+w2x2))2

</div>
</div>
<div class="layoutArea">
<div class="column">
(b) Start with the following initialization: w1 = 0.3,w2 = −0.5,x1 = 0.2,x2 = 0.4, draw the computation graph. Please use backpropagation as we did in class.

You can draw the graph on paper and insert a photo into your report.

The goal is for you to practice working with computation graphs. As a consequence, you must include the intermediate values during the forward and backward pass. Solution:

The computation graph is shown as below. All number above the lines are values in forward pass. All numbers below the lines are values in backward pass.

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
(c) Implement the above computation graph in the complimentary Colab Notebook using numpy. Use the values of (b) to initialize the weights and fix the input. Use a constant step size of 0.01. Plot the weight value w1 and w2 for 30 iterations in a single figure in the report.

Solution:

</div>
</div>
<div class="layoutArea">
<div class="column">
2. The goal of this problem is to understand the classification ability of a neural network. Specifically, we consider the XOR problem. Go to the link in footnote1 and answer the following questions. Hint: hit reset the network right next to the run button after you change the architecture.

(a) Can a linear classifier, without any hidden layers, solve the XOR problem?

Solution: No. Since there’s only one layer,it is only capable of distinguish all data with a line. It is apparently not possible to divide the data in XOR problem with a line.

1 https://playground.tensorflow.org/#activation=relu&amp;batchSize=10&amp;dataset=xor&amp;regDataset=

reg- plane&amp;learningRate=0.01&amp;regularizationRate=0&amp;noise=0&amp;networkShape=&amp;seed=0.10699&amp;showTestData= false&amp;discretize=true&amp;percTrainData=80&amp;x=true&amp;y=true&amp;xTimesY=false&amp;xSquared=false&amp;ySquared=false&amp; cosX=false&amp;sinX=false&amp;cosY=false&amp;sinY=false&amp;collectStats=false&amp;problem=classification&amp;initZero= false&amp;hideText=false

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
(b) With one hidden layer and ReLU(x) = max(0,x), how many neurons in the hidden layer do you need to solve the XOR problem? Describe the training loss and estimated

</div>
</div>
<div class="layoutArea">
<div class="column">
prediction accuracy when using 2, 3 and 4 neurons. certain number of neurons is necessary to solve XOR. Solution:

When using 2 neurons, the training loss is 0.268, the

78 = 0.78. The picture is shown as below. 100

</div>
<div class="column">
Discuss the intuition of why a

estimated prediction accuracy is

</div>
</div>
<div class="layoutArea">
<div class="column">
When using 3 neurons, the training loss is 0.260, the 73 = 0.73. The picture is shown as below.

100

</div>
<div class="column">
estimated prediction accuracy is

</div>
</div>
<div class="layoutArea">
<div class="column">
When using 4 neurons, the training loss is 0.002, the

100 = 1.00. The picture is shown as below. 100

</div>
<div class="column">
estimated prediction accuracy is

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
I think that there are 2 status for x1 and 2 status for x2. Since a layer of neurons can only perform 1 manipulation, we need 2 = 4 neurons to represent the 4 conditions when x1 xor x2. Therefore, we can use the four neurons in the hidden layers to make to right prediction.

3. In this problem, we want to build a neural network from scratch using Numpy for a real- world problem. We consider the MNIST dataset (http://yann.lecun.com/exdb/mnist/), a hand-written digit classification dataset. Please follow the formula in the complimentary Colab Notebook. Hint: Make sure you pass the loss and gradient check in the notebook.

(a) Implement the loss and gradient of a linear classifier (python function linear classifier forward and backward).

<ol start="2">
<li>(b) &nbsp;Implement the loss and gradient of a multilayer perceptron with one hidden layer and ReLU(x) = max(0, x) (python function mlp single hidden forward and backward).</li>
<li>(c) &nbsp;Implement the loss and gradient of a multilayer perceptron with two hidden layer, skip connection and ReLU(x) = max(0, x) (python function mlp two hidden forward and backward).</li>
<li>(d) &nbsp;Plot the development accuracy of each epoch of three models in a single figure using the following hyperparameters: the batch size is 50, the learning rate is 0.005 and the number of epochs is 20.

Solution:</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
(e) Try using other hyperparameters and select a set of best hyperparameters using de- velopment accuracy. Once you pick the best model and hyperparameters, include the development accuracy of each epoch into the above figure (make a new figure) and report the test accuracy of the selected model and hyperparameters.

Solution: The best parameter I currently find is BS = 100, LR = 0.01, NB EPOCH =

20. The development accuracy is 97.30%, higher than the original MLP with 2 hidden layers dev loss, which is 97.29%.

The picture is shown as below:

</div>
</div>
<div class="layoutArea">
<div class="column">
The test accuracy is 97.18%

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
