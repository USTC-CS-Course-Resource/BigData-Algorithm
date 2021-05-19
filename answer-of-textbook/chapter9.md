## Chapter 9: Classification

### Q9.2

do it later

### Q9.3
#### 1.
nearest 3 points to $x=3$ are $x_2, x_3, x_4$, where $\frac{2}{3}$ of them are labeled $+1$, 
so we predict $x=3$ as $+1$
#### 2.
nearest 3 points to $x=9$ are $x_6, x_7, x_8$, where $\frac{2}{3}$ of them are labeled $-1$, 
so we predict $x=9$ as $-1$
#### 3.
nearest 3 points to $x=-1$ are $x_1, x_2, x_3$, where $\frac{2}{3}$ of them are labeled $+1$, 
so we predict $x=-1$ as $+1$

### Q9.4
#### 1.
The only difference is adding $y_ix_i$ or $2y_ix_i$ to $w$ when updating.

This algorithm will converge **faster**, which means the $w$ will reach the optimal state $w^*$ faster. But to the end, there might be some oscillation due to the amplitude of updating.

#### 2.
**Slower**. Since $x$ are all divided by 2, the initial value will be only half of origin value. Even though when updating, the amount will be the same, but with a smaller initial value, Double-Percetron shall converge slower.

#### 3.
**The same**. There won't be any difference because for this algorithm, whether $y$ is $+1$ or $-1$ is actually symmetric.

### Q9.5
It is a table like 
|age|days since entering|total cost|profit in dollars generated|
|:-|:-|:-|:-|
and each column has a different unit.
#### 1.
**Reasonable**. Even though with different unit, but the **weight coefficients** will make up for this.
#### 2.
**Unreasonable**. The k-means algorithm uses the **distances**. Different unit will make the weight of items different.
#### 3.
**Unreasonable**. Still used **distances**.
#### 4.
**Reasonable**. Same reason as 1.

