## Chapter 2: Convergence and Sampling

### Q2.2

$Pr[X>1.5] = Pr[(X+1) > 2.5 E(X+1)] \le \frac{1}{2.5} = \frac{2}{5}$

### Q2.3
#### 1.
$E[\bar{X}]=\frac{5\times16}{16}=5$
#### 2.
$Var[\bar{X}]=\frac{25}{4}$
#### 3.
$Pr[\bar{X}>8]\le \frac{E\bar{X}}{8}=\frac{5}{8}$
#### 4.
$Pr[\bar{X}>8] = Pr[(\bar{X}-5)^2 > \frac{9}{Var(\bar{X})} Var(\bar{X})] \le \frac{Var(\bar{X})}{9}=\frac{25}{36}$
#### 5.
Recall Chernoff-Hoeffding inequality: $Pr[\bar{X}\notin E\bar{X}\pm \delta]\le 2e^{-2\delta^2 n}$
Here only need: $Pr[\bar{X} > E\bar{X} + \delta]\le e^{-2\delta^2 n}$
So $Pr[\bar{X} > 8] = Pr[\bar{X} > E\bar{X} + 3] \le e^{-2\times 3^2\times 16}=e^{-288}$
#### 6.
skipped

### Q2.5
#### 1.
$Pr[C \ge 4]=\frac{EC}{4} \le \frac{3}{4}$
$Pr[T \ge 4]=\frac{ET}{4} \le \frac{2}{4}=\frac{1}{2}$
#### 2.
$Pr[C \ge 4] = Pr[(C-EC)^2 \ge 1\times Var(C)] \le 1$
$Pr[T \ge 4] = Pr[(T-ET)^2 \ge \frac{4}{5} \times Var(T)] \le \frac{5}{4}$
> seems strange here, need to check

### Q2.6
That is $EX=82$, and $Var(X)=16$
#### 1.
$$\begin{aligned}
Pr[70 \le X \le 94] &= Pr[(X - EX)^2 < 12^2] \\
&= Pr[(X - EX)^2 < \frac{12^2}{16}Var(X)] \\
&\ge 1-\frac{16}{12^2}=\frac{1}{9}
\end{aligned}$$
#### 2.
$Pr[X < 60]=1 - Pr[X \ge \frac{60}{82}EX] \ge 1 - \frac{60}{82}=\frac{11}{41}$