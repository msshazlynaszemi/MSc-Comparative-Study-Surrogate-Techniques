# Comparative Study of Surrogate Techniques for Hyperparameter Optimization in Convolutional Neural Network (CNN) 

## Summary

<html>
<body>
<p>
  Optimizing hyperparameters in CNN is tedious for many researchers and practitioners. it requires a high degree of expertise or a lot of experience to optimize the hyperparameter and such manual optimization is likely to be biased. Hyperparameters in deep learning can be divided into two types. One type is those associated with the learning algorithms, such as determining what learning rate is appropriate, after how many iterations or epochs for each training, etc. The other type of hyperparameter is related to how we design deep neural networks. For example, how many layers we need for our network, how many filters in given convolutional layers needs, etc. Choosing different values and setting these hyperparameters correctly is often critical for reaching the full potential of the deep neural network chosen or designed, consequently influencing the quality of the produced results. Currently, different methods or approaches have been introduced in mitigating the issues of manual optimization. 
  
  These methods are such as Grid Search, Bayesian optimization, Genetic Algorithms (GA). However, these methods are still computationally expensive, largely due to the hyperparameter evaluations required. Recently, Random search has proven to be the most efficient method in hyperparameter optimization due to its simplicity, ease of implementation, and the ability to handle integer and categorical hyperparameters that naturally increase the chance of finding better hyperparameter configuration in high dimensional search space. However, what makes the adoption and application of a deep learning-based solution even more complex is that 
 
* (1) all feasible hyperparameter configurations form a huge space, from which we need to choose optimal combination, 
* (2) Different datasets require different hyperparameter configurations 
* (3) hyperparameter is optimized by only one type which is the design of deep neural network while the learning algorithms value is fixed, and that 
* (4) evaluating even a single hyperparameter configuration point in the space is often very time consuming (i.e., training one deep neural network using modern GPU usually takes hours, days, or even weeks). 
  
  One way of alleviating this burden is by constructing surrogate models, or known as a statistical model, metamodels or emulators, that is trained using a data-driven approach to approximate the simulation output accurately. Since a single evaluation of the trained surrogate model is generally faster than a single evaluation of the original simulation, performing hundreds and thousands of outputs evaluations with various combinations of design hyperparameters is no longer a problem. Although several machine learning and regression techniques have been developed for surrogate model construction, there has been little work on which surrogate techniques to apply. Hence, this research aims to address the research gap by performing a comparative study of surrogate techniques for convolutional neural network (CNN) hyperparameter optimization. 
  
  The research objective is twofold: 
* (1) to derive training datasets for surrogate techniques comparative study and 
* (2) to perform a comparative study of surrogate techniques for hyperparameter evaluation. 
  
  The hyperparameter performances were then evaluated using the state-of-the-art accuracy, mean error rate (MSE) and coefficients of determination (R2). The computational experiments revealed that gradient boosting is the best surrogate technique for hyperparameter optimization in CNN. Additionally, speed up the hyperparameter optimization in convolutional neural networks.</p>
</body>
</html>

