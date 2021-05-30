# Exercise 1

1.1

1. Find the solution to the following first-order differential equations:

$$
y'+y = e^{-2x}
$$


$$
xy'-2y = x^4
$$



**Answer**

1.( a )
$$
y' + y = e^{-2x}
$$
Solution to homogenous[齐次] pat, 

> 先求齐次式, 求不定积分

$$
y'+y=0
$$
is 
$$
\frac{dy}{dx} + y =0
$$

$$
\frac{dy}{dx} =- y
$$

$$
\frac{dy}{y} =- dx
$$

$$
\frac{dy}{y} + dx =0
$$

$$
\frac{dy}{y}+dx = 0
$$

$$
\int {\frac{dy}{y}} + \int dx = \int0
$$

$$
lny+x=lnk
$$

$$
ln\frac{y}{k}=-x
$$

$$
y=ke^{-x}
$$

Solution to nonhomogenous e.g. found using variation method 

$$
y = K(x)e^{-x}
$$
> 齐次方程通解, 通解带入原式, (前面求导+后面求导), 然后积分求出 $K(x)$ 

Thus ![image-20210412084841509](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210412084841509.png)
$$
y' + y = e^{-2x}
$$

$$
[K(x)e^{-x}]' + K(x)e^{-x} = e^{-2x}
$$

$$
[K(x)]'e^{-x} + K(x)[e^{-x}]'  + K(x)e^{-x} = e^{-2x}
$$

$$
K'(x)e^{-x}- K(x)e^{-x} + K(x)e^{-x} = e^{-2x}
$$

$$
K'(x) = e^{-x}
$$

$$
K(x) = \int e^{-x}dx+k
$$



Therefore

> $K(x)$ 代回原式

$$
K(x)=-e^{-x}+ k
$$
Hence, the solution to  (1) is
$$
y = (-e^{-x}+k)e^{-x}=-e^{-2x}+ke^{-x} ,(Check)
$$









1.( b )
$$
xy' - 2y =x^4
$$
Solutions to homogeneous equations

> 求齐次方程通解

$$
xy' - 2y = 0
$$

$$
x · \frac{dy}{dx} - 2y = 0
$$

$$
x · \frac{dy}{dx}  = 2y
$$

$$
x · dy =  2y · dx
$$

$$
\frac{dy}{y}= 2\frac{dx}{x}
$$

$$
\int \frac{dy}{y} = 2 \int{\frac{dx}{x} + \int 0 }
$$

$$
ln y = 2lnx + ln k
$$

$$
ln y = ln x^2 + lnk
$$

$$
ln y = ln ( k·x^2 )
$$

$$
y = kx^2
$$

Solution to nonhomogenous e.g. found using variation method 

$$
y = K(x)x^2
$$
Using parameter variation method, the solution to nonhomogenous e.g. is found 

> 齐次方程通解, 通解带入原式, (前面求导+后面求导), 然后积分求出 $K(x)$ 

$$
xy' - 2y =x^4
$$

$$
x [K(x)x^2]' -2 ·K(x)x^2 = x^4
$$

$$
x \{ [K(x)]'x^2 + K(x)[x^2]'\} -2 ·K(x)x^2 = x^4
$$

$$
x \{ K'(x)x^2 + K(x)2x\} -2 ·K(x)x^2 = x^4
$$

$$
 K'(x)x^3 + 2·K(x)x^2 -2 ·K(x)x^2 = x^4
$$

$$
K'(x) x^3 = x^4
$$

$$
K'(x) = x
$$

$$
\int K'(x) =\int x+ \int0
$$

$$
K(x) = \frac{1}{2} x^2 + k
$$

Thus 
$$
y = K(x) x^2
$$

$$
y =  (\frac{1}{2} x^2 + k ) x^2
$$

$$
y =  \frac{1}{2} x^4 + k·x^2, (Check)
$$





2. Verify that $y = e^{−x}$ is a solution to the differential equation $y''+2y'+y = 0$. What is special about this equation? Use method of parameter variation to find the second solution.

**Answer**

To verify  $y = e^{−x}$ 
$$
y ' = -e^{-x}
$$

$$
y'' = e^{-x}
$$



Thus, 
$$
y''+2y'+y = 0
$$

$$
e^{-x} + 2(-e^{-x})+e^{-x} = 0
$$
The special thing about the differential equation is that its characteristic e.g. has repeat roots: 
$$
\lambda^2 + 2\lambda+1 = 0
$$


Parameters variations method can be applied to 

![image-20210412111118727](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210412111118727.png)


$$
y = K(x)e^{-x}
$$
Substitution in the differential equation to obtains
$$
K''(x)e^{-x}-K'(x)e^{-x}-K'(x)e^{-x}+K(x)e^{-x}+2[K'(x)e^{-x} - K(x)e^{-x}] + K(x)e^{-x} = 0
$$

$$
K''(x)e^{-x} = 0 
$$

$$
K''(x) = 0
$$

$$
K'(x) = A , (constant)
$$

$$
K(x) = Ax + B
$$

Thus,
$$
y = (Ax +B) e^{-x}
$$

$$
y = Axe^{-x}_{\ \ \ \ second\ from P_oV_o} + Be^{-x}_{\ \ \ \ original }, complete\ solution
$$



3. Verify that $y = −cos(x)$ is a solution to the differential equation $y''−y = 2cos(x)$. Find the general solution of the equation.

> ```tex
>     line:     \ldots 
>     diagonal: \ddots 
>     vertical: \vdots
> ```
>
> $$
> line \ldots
> $$
>
> $$
> diagonal \ddots
> $$
>
> $$
> vertical \vdots
> $$
>
> ![UBhLB](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\UBhLB.jpg)



**Answer**

Considering $y=-\cos(x)$






$$
\begin{pmatrix}

-3a_1 + 2 a_0 = 0 
\\ 2a_1=4
\\ 2b = 1
\\ -2c_1 + bc_2 = 1
\\ -2c_2 -bc_1 = 0 

\end{pmatrix}

\rightarrow

\begin{Bmatrix}




\end{Bmatrix}
$$




4. Find the particular solution[特解] of the differential equation $y''−3y'+2y = 4x + e^{3x} + sin(2x)$ . What is the general solution to the equation?

**Answer**

The particular solution, $y_p$, has an expression ( shape ), similar to the excitation function, i.e.
$$
y_p =a_0 + a_1x
$$






5. Find the solution to $y'' + y = sin(5t)$ . If the input to this differential equation, $sin(5t)$, (providing the forced oscillation) is replaced by $sin(t)$, find the solution.

   Note: 

   
   $$
   y' = \frac{d}{dx}y \ and \ y'' = \frac{d^2}{dx^2}y
   $$
   (derivatives are with respect to x)
$$
   y' =\frac{d}{dt}y\ and\ y''=\frac{d^2}{dt^2}y
$$

​	   (derivatives are with respect to t)

**Answer**



# Exercise 2

### P1 Find the relationship between the output voltage and input voltage in the following circuits both in the time-domain and in the Laplace-domain. Assuming the initial conditions for C and L are zero and the excitation is impulsive find the behaviour of the output voltage.

### P2 If the impulsive excitation is replaced by a sinusoidal excitation, find the frequency domain voltage transfer function for each case.

### P5 Then find the mag. and phase of each transfer function.

![image-20210412171719058](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210412171719058.png)

![image-20210412171807625](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210412171807625.png)

**Answer:**

![image-20210529205254309](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210529205254309.png)

writing voltage  around the 

> 电容是 1/C 积分 i(t)

$$
+ R_i(t) + \frac{1}{C}\int i(t)dt +R_2 i(t) = V_i(t)
$$

$$
-V_i(t) + R_i(t) + \frac{1}{C}\int i(t)dt +R_2 i(t) = 0
$$

where
$$
i(t) =\frac{V_2(t)}{R_2}
$$
Differentiate $-V_i(t) + R_i(t) + \frac{1}{C}\int i(t)dt +R_2 i(t) = 0$ with respect to i

> 同时求导

$$
 -\frac{d V_i(t)}{dt} + R_1 \frac{d i(t)}{dt} + \frac{1}{C}i(t) + R_2 \frac{d i(t) }{dt} = 0
$$





### P2 If the impulsive excitation is replaced by a sinusoidal excitation, find the frequency domain voltage transfer function for each case.

![image-20210530123836468](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210530123836468.png)


$$
i(t) = i_1(t) +i_2(t)
$$
Therefore,
$$
i(t) 
$$




### P5 Then find the mag. and phase of each transfer function.

![image-20210530123513220](D:\W_WORKSPACE\E_ESSEX\CE223\CE223_MD\CE223_ProblemSet.assets\image-20210530123513220.png)

This is    from the circuit
$$
i(t) = i_1(t)+i_2(t)
$$
therefore

> 并联  1/R, 1/L，C

$$
i(t) = \frac{V_o(t)}{R}+C\frac{dV_o(t)}{dt}
$$























# Exercise 3









#  Exercise 4

