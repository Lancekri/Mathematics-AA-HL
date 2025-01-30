# Unit Test 2: Statistics and Probability
## Question 1 
<p>Box 1 contins 5 red balls and 2 white balls.<br>Box 2 contins 4 red balls and 3 white balls.</p>

**a) $A$ box is chosen at random and a ball is drawn. Find the probability that the ball is red.** (3 marks)<br>
<details>
  <summary>Answer</summary>
<p>Red Box 1 $= \frac{1}{2} \cdot \frac{5}{7}$<br><br>
Red Box 2 $= \frac{1}{2} \cdot \frac{4}{7}$<br><br>
$P(R) = \frac{3}{14} + \frac{4}{14} = \frac{9}{14}$<br></p>

<p>Let $A$ be the event that "box 1 is chosen" and let $R$ be the event that "a red ball is drawn".</p>
</details>

**b) Determine whether events $A$ and $R$ are independent.** (2 marks)<br>
<details>
  <summary>Answer</summary>
If $A$ and $R$ are independent $\Rightarrow P(A\cap B) = P(A)P(B)$
- $P(A\cap R) = \frac{1}{2} \times \frac{5}{7} = \frac{5}{14}$
- $P(A)P(R) = \frac{1}{2} \times \frac{9}{14} = \frac{9}{28}$ <br>
$\therefore$ $A$ and $R$ are not independent
</details>

## Question 2
<p>A factory manufactures lamps. It is known thhat thee probability that a lamp is found to be defective is $0.05$. A rndom sample of $30$ lamps is tested.</p>

**a) Find the probability that there is at least one defective lamp in the sample.** (3 marks)<br>
<details>
  <summary>Answer</summary>
  $X \sim B(30, 0.05)$<br>
$\therefore$ $P(X \ge 1) = 1 - P(X=0)$<br>
$\quad \quad \quad \quad \quad = 1 - (1 - 0.05)^2$<br>
$\quad \quad \quad \quad \quad = 0.785$<br>
</details>

**b) Given that there is at least one defective lamp in the sample, find the probability that there are at most two defective lamps.** (4 marks) <br>
<details>
  <summary>Answer</summary>
  $P(X \le 3 | X \ge 1) = \frac{P(X=1) + P(X=2)}{P(X\ge 1)}$ <br> <br>
$\quad \quad \quad \quad \quad \quad \quad = \frac{0.338 + 0.259}{0.785} = \fbox{0.761}$
</details>

## Question 3
A continuous random variable X has the probability density function:
$$f(x) = \left( \frac{x}{2} \right)$$
<details>
  <summary>Answer</summary>
  
</details>

## Question 4
Events $A$ and $B$ are independent and $P(A) = 3P(B)$. <br>
Given $P(A\cup B) = 0.68$, find $P(B)$. (6 marks)<br>


## Question 5
Consider the set of six-digit positive intergers that can be formed from the digits 0, 1, 2, 3, 4, 5, 6, 7, 8 and 9.<br>
<br>
Find the total number of six-digit positive intergers that can be formed such that:<br>
**(a) the digits are distinct;** (2 marks)<br>
$9 \times ^9P_5 = 136080$<br>
**(b) the digits are distinct and are in increasing order.** (2 marks)<br>
$^9C_4 = 84$
