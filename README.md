# Single Neuron Decision Boundary.

Project Description: http://ranger.uta.edu/~kamangar/CSE-5368-FA18/Assignment02(Duedate.Sept.23,2018).html

### __Description__  
Apply decision boundary to set of numbers on 2D coordinates.
The purpose of the this assignment is to practice with a `single neuron decision boundary and learning rule.`
 
Write a program to display the decision boundary for a single neuron with two inputs.
Your program should:

- [x] Draw the boundary.
- [x] Display the region of the input space which corresponds to the positive output of the neuron  in green color.
- [x] Display the region of the input space which corresponds to the negative output of the neuron  in red color.

Your program should also include 3 sliders, 2 buttons, and one drop down selection box.
 
### Sliders
- __Slider 1__: Change w1 (first weight) between `-10 and 10.` Default value = 1
- __Slider 2__: Change w2 (second weight) between `-10 and 10.` Default value = 1
- __Slider 3__: Change b (bias between `-10 and 10.` Default value=0

 
### Buttons
- __Button1:__ Train. Clicking this button should adjust the weights and bias for 100 steps using the learning rule. `Wnew =Wold + epT`  where  `e = t – a`
- __Button 2:__ Create random data. Assuming that there are only two possible target values `1 and -1 (two classes)`, this button should create 4 random data points (two points for each class). The range of data points should be from `-10 to 10` for both dimensions.

 
## Drop Down Selection.
- The drop down box should allow the user to select between three transfer functions `(Symmetrical Hard limit, Hyperbolic Tangent, and Linear)`

 
### Notes:
>   - Changing any of the parameters should immediately be reflected in the displayed output.
>   - Displayed range of input space should be from `-10 to 10` for both dimensions.
>   - Resolution of the input space should be `100 by 100`
>   - Assume that there are only two possible classes. The target value for one class should be 1 and for the other class should be -1.
>   - The learning rule for this assignment is the same as the Perceptron learning rule which is designed for the hardlimit transfer function. Applying the same rule to hyperbolic tangent and linear transfer function does not exactly correspond to the Perceptron learning rule and may create contradictory situations. However experimenting with these transfer functions will give you insight into the gradient descent in the upcoming topics.
