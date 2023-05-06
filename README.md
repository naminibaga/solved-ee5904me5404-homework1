Download Link: https://assignmentchef.com/product/solved-ee5904_me5404-homework1
<br>
<strong>Q1</strong>.

Consider the signal-flow graph of the perceptron shown in the above figure. The activation function, ( )<em>v </em>, where v is the induced local field, can be designed by the user. If the activation function is chosen as hard limiter (i.e. step function), then it becomes the classical perceptron, and the decision boundary is shown to be a hyperplane.  In this problem, let’s explore other choices of the activation function, and its effect on the decision boundary.  Let’s assume that the classification decision made by the perceptron is simply a threshold rule defined as follows:

<em>Observation vector x x x</em>[ <sub>1      2                      </sub><em>x </em>] <em>belongs to class C<sub>1</sub> if the output y &gt;</em>ξ<em>, where</em>ξ<em>is a user-defined threshold; otherwise, x belongs to class C<sub>2</sub>. </em>




Consider the following three choices of activation function:

1) The activation function is a quadratic function: ( )<em>v </em>  (<em>v a</em>)<sup>2    </sup>c;

1<em>e</em><em>v </em>2) The activation function is the hyperbolic tangent function: ( )<em>v </em>1<em>e</em><sub></sub><em><sub>v </sub></em>;

(<em>v m</em> )<sup>2</sup>

3) The activation function is the Bell-shaped Gaussian function: ( )<em>v </em><em>e</em><sup> </sup><sup>2 </sup>. For each case, investigate whether the resulting decision boundary is a hyper-plane or not.

<strong>Q2</strong>.

Consider the logic function, EXCLUSIVE OR (XOR).  Truth Table of XOR

<table width="139">

 <tbody>

  <tr>

   <td width="35">x<sub>1</sub></td>

   <td width="26">0</td>

   <td width="26">1</td>

   <td width="26">0</td>

   <td width="26">1</td>

  </tr>

  <tr>

   <td width="35">x<sub>2</sub></td>

   <td width="26">0</td>

   <td width="26">0</td>

   <td width="26">1</td>

   <td width="26">1</td>

  </tr>

  <tr>

   <td width="35"><em>y </em></td>

   <td width="26">0</td>

   <td width="26">1</td>

   <td width="26">1</td>

   <td width="26">0</td>

  </tr>

 </tbody>

</table>




It is well known that the XOR problem is not linearly separable. It seems obvious by visually checking, which however cannot be accepted as mathematical proof. Therefore, please supply a rigorous mathematical proof for this statement.




<strong>Q3</strong>.

The perceptron could be used to perform numerous logic functions, such as AND, OR, COMPLEMENT and NAND function, whose truth tables are tabulated as follows respectively.




<table width="429">

 <tbody>

  <tr>

   <td width="35">x1</td>

   <td width="35">0</td>

   <td width="35">0</td>

   <td width="35">1</td>

   <td width="35">1</td>

   <td rowspan="3" width="81"> </td>

   <td width="36">x1</td>

   <td width="34">0</td>

   <td width="35">0</td>

   <td width="34">1</td>

   <td width="35">1</td>

  </tr>

  <tr>

   <td width="35">x2</td>

   <td width="35">0</td>

   <td width="35">1</td>

   <td width="35">0</td>

   <td width="35">1</td>

   <td width="36">x2</td>

   <td width="34">0</td>

   <td width="35">1</td>

   <td width="34">0</td>

   <td width="35">1</td>

  </tr>

  <tr>

   <td width="35">y</td>

   <td width="35">0</td>

   <td width="35">0</td>

   <td width="35">0</td>

   <td width="35">1</td>

   <td width="36">y</td>

   <td width="34">0</td>

   <td width="35">1</td>

   <td width="34">1</td>

   <td width="35">1</td>

  </tr>

 </tbody>

</table>




<h1>                           AND                                                                                OR</h1>




<table width="395">

 <tbody>

  <tr>

   <td width="163">


    <table width="105">

     <tbody>

      <tr>

       <td width="35">x</td>

       <td width="35">0</td>

       <td width="35">1</td>

      </tr>

      <tr>

       <td width="35">y</td>

       <td width="35">1</td>

       <td width="35">0</td>

      </tr>

     </tbody>

    </table></td>

   <td width="232">


    <table width="174">

     <tbody>

      <tr>

       <td width="35">x1</td>

       <td width="35">0</td>

       <td width="35">0</td>

       <td width="35">1</td>

       <td width="35">1</td>

      </tr>

      <tr>

       <td width="35">x2</td>

       <td width="35">0</td>

       <td width="35">1</td>

       <td width="35">0</td>

       <td width="35">1</td>

      </tr>

      <tr>

       <td width="35">y</td>

       <td width="35">1</td>

       <td width="35">1</td>

       <td width="35">1</td>

       <td width="35">0</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<h1>                     COMPLEMENT                                                                    NAND</h1>




a). Demonstrate the implementation of the logic functions AND, OR, COMPLEMENT and NAND with selection of weights by off-line calculations.




b). Demonstrate the implementation of the logic functions AND, OR, COMPLEMENT and NAND with selection of weights by learning procedure. Suppose initial weights are chosen randomly and learning rate  is 1. Plot out the trajectories of the weights for each case. Compare the results with those obtained in (a). Try other learning rates, and report your observations with different learning rates.




c). What would happen if the perceptron is applied to implement the EXCLUSIVE OR function with selection of weights by learning procedure? Suppose initial weight is chosen randomly and learning rate  is 1.0. Do the computer experiment and explain your finding.                                                  (3 Marks) <strong>Q4. </strong>(10 Marks)

Single layer perceptron with pure linear activation function can be used to fit a linear model to a set of input-output pairs. Suppose that we are given the following pairs:

{(0.5,8.0), (1.5, 6.0), (3, 5), (4.0, 2), (5.0, 0.5)} and a single linear neuron as shown in the following figure.







a). Find the solution of w and b using the standard linear least-squares (LLS) method. Plot out the fitting result.

(3 Marks)

b). Suppose that initial weight is chosen randomly and learning rate  is 0.02. Find the solution of w and b using the least-mean-square (LMS) algorithm for 100 epochs. Plot out the fitting result and the trajectories of the weights versus learning steps. Will the weights converge?

(3 Marks)

c). Compare the results obtained by LLS and the LMS methods.

(2 Marks)

<ol>

 <li>d) Repeat the simulation study in b) with different learning rates , and explain your findings.</li>

</ol>

(2 Marks)

<strong> </strong>

<strong>Q5. </strong>(10 Marks)

In a variant of the LMS algorithm called the <em>leaky LMS algorithm</em>, the cost function to be minimized is defined by

1 <sup>2                    </sup>1                <sup>2</sup>

<em>E n</em>( )  <em>e </em>( )<em>n </em> || <em>w n</em>( ) ||

2             2

where w(n) is the weight vector, e(n) is the estimation error, and λ is a positive constant. As in the ordinary LMS algorithm, we have the estimation error,

<em>e n</em>( )  <em>d n</em>( )  <em>w</em><em><sup>T</sup></em>( ) ( )<em>n x n</em>

where d(n) is the desired response corresponding to the input vector x(n).




Following the similar procedure to derive the learning algorithm for LMS, show that the time update for the weight vector of the leaky LMS algorithm is defined by

<em>w</em>(<em>n</em>1)(1)<em>w</em>(<em>n</em>)<em>x</em>(<em>n</em>)<em>e</em>(<em>n</em>)

which includes the ordinary LMS algorithm as a special case.


