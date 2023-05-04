Download Link: https://assignmentchef.com/product/solved-cs60050-assignment-3-svm-ann
<br>
Assignment 3: SVM &amp; ANN

<ol>

 <li>Perform the following implementation and analysis of binary SVM classification on the provided data 40 marks</li>

 <li>Randomly pick 80% of the data as a training set and the rest as a test set.</li>

</ol>

Implement the binary SVM classifier using the following kernels:

<ol>

 <li>Linear</li>

 <li>Quadratic</li>

</ol>

<ul>

 <li>Radial basis function</li>

</ul>

<ol>

 <li>Report both the training and test set classification accuracies for the most suitable value of generalization constant C for each of the three kernels. Consider C empirically. Report the accuracy in the form of a comparison table with corresponding C values (C value which provides the best test set accuracy is the most suitable one out of all those different trial values that you try.)</li>

</ol>

<ol start="2">

 <li>Build a MLP classifier for the given dataset. Use stochastic gradient descent optimiser for the models. Find the number of nodes in the input and output layer according to the</li>

</ol>

dataset and justify it in the report. Randomly pick 80% of the data as a training set and

the rest as a test set. Use packages of pytorch.

<ol>

 <li>Vary the number of hidden layers and number of nodes in each hidden layer as follows. 20 marks

  <ol>

   <li>0 hidden layer</li>

   <li>1 hidden layer with 2 nodes iii. 1 hidden layer with 6 nodes</li>

   <li>2 hidden layers with 2 and 3 nodes respectively v. 2 hidden layers with 3 and 2 nodes respectively</li>

  </ol></li>

 <li>For each of the architectures, vary the learning rates as 0.1, 0.01, 0.001, 0.0001, 0.00001. Plot graph for the results with respect to accuracy. (Learning rate vs accuracy for each model and model vs accuracy for each learning rate.)</li>

 <li>Mention the architecture and hyper parameters (including optimizer and learning rate) of the best found model in the report. Try to justify it.</li>

 <li>(Optional) Compare execution time in CPU and GPU for each model. Conclude your findings.</li>

</ol>

<ol start="3">

 <li>Compare the performances of both the classifiers.</li>

</ol>