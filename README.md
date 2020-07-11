## Task description ##

Two integer signed numbers and two positions of bits `i` and `j` (`i < j`) are given. Implement the algorithm for inserting one number into another according to the following rule - take the first `j - i + 1` bits from the source number and replace by them bits from the `i`-th to `j`-th destination numbers (bits are numbered from left to right). **Use only bit operations to solve.**
> **Source number = 655, Destination number = 2728, i = 3, j = 8, Result = 2680**
> ![Scheme](Scheme1.png)


> **Source number = 5440, Destination number = -2223, i = 18, j = 23, Result = -16517295**
> ![Scheme](Scheme2.png)
>
*Topics - bit operations.*