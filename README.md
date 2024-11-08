# Binomial Random Variable Proof using Marble Draw from a Bag Simulation
![S__120233986](https://github.com/user-attachments/assets/2cdd61ef-869e-4ea0-9d87-433164529191)
<img src="https://github.com/user-attachments/assets/c3ce8ec2-82fb-4f75-93a6-82768a2da719" width="100%" height="500" alt="Image 1">

The purpose of this repository is to see if this guy, the "Binomial Random Variable" is capping us or not. By using marbel draw from a bag to test. <br><br>

## Overview & Control Variable
- In this experiment number of trial(n) in each scenerio is 10
- When we pulled the marble out of the bag, we just put it back in, so that it could be an Independent Trial
- P(success) every trial is constant (because we put marble back in the bag)
- 10 Million time of simulation
<br>

## Hypothesis
P(k n) is a probability of success k time in n trial <br>
P(k n) = nCk × pᵏ × (1-p)ⁿ⁻ᵏ <br>

### First Scenerio
<img src="https://github.com/user-attachments/assets/4de41333-adc9-42fb-b239-f361b9764c7c" width="300" height="120" alt="Image 1"> <br>

Bag : Red Green Green <br>
Success(k) is when drawing Red Marbel <br>
P(0 10) &nbsp;&nbsp;= 10C0 (1/3)⁰(2/3)¹⁰ &nbsp;           ≈ 0.01734153 &nbsp;(1.734153%)<br>
P(1 10) &nbsp;&nbsp;= 10C1 (1/3)¹(2/3)⁹ &nbsp;&nbsp;&nbsp;≈ 0.08670765 &nbsp;(8.670765%)<br>
P(2 10) &nbsp;&nbsp;= 10C2 (1/3)²(2/3)⁸ &nbsp;&nbsp;&nbsp;≈ 0.19509221 &nbsp;(19.509221%)<br>
P(3 10) &nbsp;&nbsp;= 10C3 (1/3)³(2/3)⁷ &nbsp;&nbsp;&nbsp;≈ 0.26012295 &nbsp;(26.012295%)<br>
P(4 10) &nbsp;&nbsp;= 10C4 (1/3)⁴(2/3)⁶ &nbsp;&nbsp;&nbsp;≈ 0.22760758 &nbsp;(22.760758%)<br>
P(5 10) &nbsp;&nbsp;= 10C5 (1/3)⁵(2/3)⁵ &nbsp;&nbsp;&nbsp;≈ 0.13656455 &nbsp;(13.656455%)<br>
P(6 10) &nbsp;&nbsp;= 10C6 (1/3)⁶(2/3)⁴ &nbsp;&nbsp;&nbsp;≈ 0.05690190 &nbsp;(5.690190%)<br>
P(7 10) &nbsp;&nbsp;= 10C7 (1/3)⁷(2/3)³ &nbsp;&nbsp;&nbsp;≈ 0.01625768 &nbsp;(1.625768%)<br>
P(8 10) &nbsp;&nbsp;= 10C8 (1/3)⁸(2/3)² &nbsp;&nbsp;&nbsp;≈ 0.00304832 &nbsp;(0.304832%)<br>
P(9 10) &nbsp;&nbsp;= 10C9 (1/3)⁹(2/3)¹ &nbsp;&nbsp;&nbsp;≈ 0.00033870 &nbsp;(0.033870%)<br>
P(10 10) = 10C10 (1/3)¹⁰(2/3)⁰                            ≈ 0.00001694 &nbsp;(0.001694%)<br>

### Second Scenerio
<img src="https://github.com/user-attachments/assets/031fb3d3-bb28-4d75-8bf7-c91a7d463911" width="300" height="90" alt="Image 1"> <br>

Bag : Red Green Green Green <br>
Success(k) is when drawing Red Marbel <br>
P(0 10) &nbsp;&nbsp;= 10C0 (1/4)⁰(3/4)¹⁰ &nbsp;           ≈ 0.05631351 &nbsp;(5.631351%)<br>
P(1 10) &nbsp;&nbsp;= 10C1 (1/4)¹(3/4)⁹ &nbsp;&nbsp;&nbsp;≈ 0.18771172 &nbsp;(18.771172%)<br>
P(2 10) &nbsp;&nbsp;= 10C2 (1/4)²(3/4)⁸ &nbsp;&nbsp;&nbsp;≈ 0.28156757 &nbsp;(28.156757%)<br>
P(3 10) &nbsp;&nbsp;= 10C3 (1/4)³(3/4)⁷ &nbsp;&nbsp;&nbsp;≈ 0.25028229 &nbsp;(25.028229%)<br>
P(4 10) &nbsp;&nbsp;= 10C4 (1/4)⁴(3/4)⁶ &nbsp;&nbsp;&nbsp;≈ 0.14599800 &nbsp;(14.599800%)<br>
P(5 10) &nbsp;&nbsp;= 10C5 (1/4)⁵(3/4)⁵ &nbsp;&nbsp;&nbsp;≈ 0.05839920 &nbsp;(5.839920%)<br>
P(6 10) &nbsp;&nbsp;= 10C6 (1/4)⁶(3/4)⁴ &nbsp;&nbsp;&nbsp;≈ 0.01622200 &nbsp;(1.622200%)<br>
P(7 10) &nbsp;&nbsp;= 10C7 (1/4)⁷(3/4)³ &nbsp;&nbsp;&nbsp;≈ 0.00308990 &nbsp;(0.308990%)<br>
P(8 10) &nbsp;&nbsp;= 10C8 (1/4)⁸(3/4)² &nbsp;&nbsp;&nbsp;≈ 0.00038624 &nbsp;(0.038624%)<br>
P(9 10) &nbsp;&nbsp;= 10C9 (1/4)⁹(3/4)¹ &nbsp;&nbsp;&nbsp;≈ 0.00002861 &nbsp;(0.002861%)<br>
P(10 10) = 10C10 (1/4)¹⁰(3/4)⁰                            ≈ 0.00000095 &nbsp;(0.000095%)<br>

## Result from Simulation
### First Scenerio
<img src="https://github.com/user-attachments/assets/5f9f731e-3ee7-4859-b954-17ea49e2ef93" width="35%" height="300" alt="Image 1">
<img src="https://github.com/user-attachments/assets/508043df-37b1-411c-87e7-6da7190bbf29" width="35%" height="300" alt="Image 2">
<img src="https://github.com/user-attachments/assets/c4d55467-7a35-49f4-bd20-1abc596d2f8f" width="20%" height="300" alt="Image 3">

### Second Scenerio
<img src="https://github.com/user-attachments/assets/61883594-d729-412e-b2cb-6d3e5717e0ec" width="35%" height="300" alt="Image 1">
<img src="https://github.com/user-attachments/assets/67c941ed-f4c4-4ebb-96e1-48223afa92ca" width="35%" height="300" alt="Image 2">
<img src="https://github.com/user-attachments/assets/2c8ca9f6-d791-40ed-a188-1dd5cb5adc38" width="20%" height="300" alt="Image 3">

## Conclusion
Experimental probability and theoretical probability are very close. The "Binomial Random Variable" is accurate.

