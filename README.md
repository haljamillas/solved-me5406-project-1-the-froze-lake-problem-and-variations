Download Link: https://assignmentchef.com/product/solved-me5406-project-1-the-froze-lake-problem-and-variations
<br>
This project is designed for the student to demonstrate (through independent learning):

<ol>

 <li>Competence in implementing a set of modelfree reinforcement learning techniques in a small scale problem setting, and</li>

 <li>Understanding of the principles of, and implementation issues related to, this set of techniques.</li>

 <li>PROBLEM STATEMENT</li>

</ol>

Consider a frozen lake with (four) holes covered by patches of very thin ice. Suppose that a robot is to glide on the frozen surface from one location (i.e., the top left corner) to another (bottom right corner) in order to pick up a frisbee, as is illustrated in Figure 1.

Fig. 1: A robot moving on a frozen lake.

The operation of the robot has the following characteristics:

<ol>

 <li>At a state, the robot can move in one of four directions, left, right, up, and down.</li>

 <li>The robot is confined within the grid.</li>

 <li>The robot receives a reward of (i) +1 if it reaches the frisbee, (ii) −1 if it falls into a hole, and (iii) 0 for all other cases.</li>

 <li>An episode ends when the robot reaches the frisbee or falls into a hole.</li>

</ol>

III. REQUIREMENT

<h1>A. What to be done</h1>

Three tasks as described below are to be completed for this project. The percentage associated with each task indicates the mark weightage.

<u>Task 1</u>: Basic implementation (25%)

Write a Python program to compute an optimal policy for the Frozen Lak problem as described in Section II, using the following three tabular (i.e., not involving any use of a neural network) reinforcement learning techniques:

<ol>

 <li>First-visit Monte Carlo control without exploring starts.</li>

 <li>SARSA with an <em>ϵ</em>-greedy behavior policy.</li>

 <li><em>Q</em>-learning with an <em>ϵ</em>-greedy behavior policy.</li>

</ol>

You can set the values for all the necessary parameters, such as discount rate, learning rate, etc.

<u>Task 2</u>: Extended implementation (25%)

<table width="672">

 <tbody>

  <tr>

   <td width="672">PETER C. Y. CHEN, 2020                                                                                                                                                                                                                                                                                                  2</td>

  </tr>

 </tbody>

</table>

Increase the grid size to at least 10×10 while maintaining the same proportion between the number of holes and the number of states (i.e., 4<em>/</em>16=25%). Distribute the holes randomly without completely blocking access to the frisbee. Repeat Task 1.

<u>Task 3</u>: Report (50%)

Write an <u>individual </u>report that describes the implementation and discusses the results. This report should be <u>no more </u>than 10 pages (excluding the cover page). Compare and contrast the performance of the three reinforcement learning techniques and the results that they have generated in your implementations. Discuss the difficulties encountered and describe how they were overcome during the project. Elaborate on your own initiatives (if any) to investigate and improve the efficiency of these techniques in solving the given problem.

<h1>B. Python programming</h1>

For setting up the “frozen lake environment”, you can use publicly available toolkits (such as OpenAI gym) or write the code yourself. The advantage of the latter option is that you will learn how to implement the “low-level” features of a reinforcement learning problem.

Your Python code must be able to run under Python 3.6, either as a Jupyter Notebook or in plain Python code, and use only standard and publicly available packages. For programming, the PyCharm integrated development environment is recommended.

Coding convention is to be observed. In particular, clear and concise comments should be included in the source code to explain various

calculation steps, e.g., how the number of first visits to a state-action pair is computed, and how an exploratory action in SARSA and <em>Q</em>-learning is selected, etc. The explanation should be detailed and specific; brief and general comments such as <em>“These lines compute the value for [something]” </em>are not adequate.

<ol>

 <li></li>

</ol>