---
title: Intro to Undergrad Math
subtitle: A perspective
date: 2026-02-07T00:00:00+05:30
layout: single
---

## Highlighted Ideas in *Analysis*.

I have chosen to highlight two core ideas from analysis for undergrads. I cannot condense analysis into some paragraphs but I believe these two ideas will help in highlighting motivations behind concepts. I begin with functions; functions are present in almost all branches of math and mathematical sciences. The idea of a function is formalized in mathematics not as just an input-output machine; but as *arbitrary correspondences*. $J = \left\{(x,\Delta),(y,\square),(z,\square),(k,\circ)\right\}$ is an example of a function. We are able to look under the curtain and see that is just a set, a set with some elements, elements that are ordered; a letter and then a shape. You may realize that it saying precisely what we require out of a function, that is, association of an 'input' with some 'output'. We feel confident to state a definition now. A function $F:A\to B$ is the set whose elements are ordered pairs which look like $(a,b)$ where $a$ comes from the set $A$ and $b$ comes from set $B$.


> *Why did we make the definition this way?*

There is a rich history behind this; alternate definitions were limited and broke under pressure.

Shifting our focus to sequences, first we state that sequences are just functions (with some special stuff). A sequence, lets suppose $S = \left\{(0,\ \ ),(1,\cdot),(2,-),(3,\Delta),(4,\square),(5,{\LARGE\star}),\dots\right\}$, associates natural numbers to some *objects*. Looking at $S$ we can see that to each natural number is associating a geometrical object and a lucky guess suggests that the number tells how many vertices the associated shape has, and we would be right. Lets be bold and make one more guess, looking the first 5 terms we see that all the objects can be drawn without lifting our pencil and not going through an already made line. But this guess fails at the $6^{th}$ term $(5,{\LARGE\star})$ as this star shape cannot be drawn without lifting our pencil or going over a line which was already drawn. So sometimes our intuition fails with sequences.

> *Under what conditions our predictions about the behaviour of sequences match which their actual tendencies? Can the sequences be put inside our box of understanding or will it eventually go beyond?*

## Highlighted Ideas in *Algebra*.

We have an established idea of adding two numbers, multiplying them and doing various other operations. In algebra, students encounter these operations under a different light. We have an understanding of what it means to *ADD* two *Numbers*, so we can think about what it means to add two things which are not exactly numbers. Addition of numbers has some nice properties, we can see whether our new way of adding things also has these nice properties or we have to make some leaps. Think about adding two *people* together. Let $P_1$ and $P_2$ be two people, and we say that the word "Join\" is our way of adding two people. We will write their sum as $P_1 \ Join \ P_2$. We still don't know what Join means. Say, Join means that one person is having dinner already and the other one joins that person for having food. So, if someone says $P_1 \ Join \ P_2$, we know that $P_1$ sat together with $P_2$ and ate dinner together. Having established our new way of adding people lets think about one property that addition of numbers has: $a+b=b+a$ if $a,b$ are numbers. Lets see if we have this property in our addition of people. Is $P_1 \ Join \ P_2=P_2 \ Join \ P_1$? $P_2 \ Join \ P_1$ states that it was $P_2$ who joined $P_1$ (that and $P_1$ was the one who was already having food). So we can see that here, the order changes the meaning so $P_1 \ Join \ P_2\neq P_2 \ Join \ P_1$. Also notice that adding two numbers gives us a number but addition of people does not result in a person, it results in a dinner. It seems that its not possible to leave the realm of numbers by our usual addition; we can leave the set of people using *Join*.


> *Under what conditions can we add, subtract, multiply and divide? What do these even mean when we are applying on things which are not our usual numbers? What are other operations and other objects? What can we say about their properties (such as the order in which they are applied)?*

## Highlighted Ideas in *Linear Algebra*.

Motivations behind linear algebra were to generalize (linear) equation solving and geometrical objects like "2-D Vectors".

Lets stay in the realm of 2-D vectors. There are few things we can do to manipulate these vectors; rotating and elongation (shrinking is considered as elongating but in the opposite way; *opposite ways* will be thoroughly studied in an algebra course). These manipulations can be done by multiplying a $2\times 2$ matrix with our $2\times 1$ vector (Think about how this multiplication is defined and how it lacks some nice properties of our usual multiplication of numbers). $$\begin{pmatrix}
a & b \\
c&d
\end{pmatrix}
\begin{pmatrix}
x\\
y 
\end{pmatrix}=
\begin{pmatrix}
(ax+by)\\
(cx+dy)
\end{pmatrix}
$$ So the resulting vector will be a rotated and scaled version our original version. A matrix is a big thing, here it has $4$ numbers inside it. A lot more information is packed than just one single number. We can multiply vectors by matrices as well as just numbers: $$0.5\begin{pmatrix}
x\\
y 
\end{pmatrix}=
\begin{pmatrix}
x/2\\
y/2 
\end{pmatrix}
$$ Multiplication by numbers just results in shorter/longer vector (no rotation). Lets look at an example: $$\begin{pmatrix}
0.8 & 0.3 \\
0.2&0.7
\end{pmatrix}
\begin{pmatrix}
1 \\
-1
\end{pmatrix}$$ which gives us a vector $\begin{pmatrix}
1/2 \\
-1/2
\end{pmatrix}$ which we know is just $0.5\begin{pmatrix}
1 \\
-1
\end{pmatrix}$. So what we have just noticed that $$\begin{pmatrix}
0.8 & 0.3 \\
0.2&0.7
\end{pmatrix}
\begin{pmatrix}
1 \\
-1
\end{pmatrix}=0.5\begin{pmatrix}
1 \\
-1
\end{pmatrix}
.$$ So we can see that this matrix with $4$ numbers inside just acts as the number $0.5$ when applied to vectors. Clearly not all matrices are like this, so whats so special about this matrix. Lets apply this matrix on another vector just in case; $$\begin{pmatrix}
0.8 & 0.3 \\
0.2&0.7
\end{pmatrix}
\begin{pmatrix}
2 \\
5
\end{pmatrix}.$$ We get $\begin{pmatrix}
3.1 \\
3,9
\end{pmatrix}$. So here the resultant vector is not like a its original vector (we cannot write the result as multiplication of number and vector this time).

> *When does a matrix act just like a number? Is the matrix special or is the vector special or do they come in pair?*

For your time, *Merci* :)
