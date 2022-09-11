# **Vector2D Cheat Sheet**
#### <ins>Vectors</ins>  
A vector is an arrow with a lenght and a direction.  
$\vec{a}$  
A vector contains two coordinates describing how long the vector is in the direction of the x and the y axis.  
$\vec{a}=({a_1 \atop a_2})$  
When drawing a vector into your coordinate system, it does not matter where you start, as long as the arrow has the same length and direction.  
[Examples of plotting vectors into your coordinate system](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-plotting-vectors-into-your-coordinate-system)

#### <ins>Addition of vectors</ins>  
$\vec{a}+\vec{b}=({a_1 + b_1 \atop a_2 + b_2})$  
Properties/rules of vector adding: 
- $\vec{a}+\vec{b}=\vec{b}+\vec{a}$
- $\vec{a}+\vec{0}=\vec{a}$
- $k(\vec{a}+\vec{b})=k\vec{a}+k\vec{b}$
- $\vec{a}+(\vec{b}+\vec{c})+\vec{c}$  

[Examples of vector adding](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-vector-adding)  

#### <ins>Subtraction of vectors</ins>  
$\vec{a}-\vec{b}=({a_1-b_1 \atop a_2-b_2})$  

[Examples of vector subtraction](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-vector-subtraction)  
#### <ins>Multiply constant onto vector</ins>  
$k\times ({x \atop y})=({k\times x \atop k\times y})$  

[Examples of multiplying a constant onto a vector](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-multiplying-a-constant-onto-a-vector)  
#### <ins>Dot product</ins>  
$({x_1 \atop y_1})\cdot({x_2 \atop y_2})=x_1\times x_2 + y_1 \times y_2$  
[Examples of dot product](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-dot-product)  

#### <ins>Length of a vector</ins>  
$|\vec{a}|=\sqrt{x^2+y^2}$  
Properties/rules of the lenght of a vector:  
$|k\times \vec{a}|=k\times |\vec{a}|$  
$|\vec{a}|^2=\vec{a}\cdot\vec{a}$  
[Examples of the lenght of a vector](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-the-lenght-of-a-vector)  

#### <ins>Vector argument</ins>  
$arg(\vec{a})=sin^{-1}(\frac{y}{\sqrt{x^2+y^2}})$ $=cos^{-1}(\frac{x}{\sqrt{x^2+y^2}})=tan^{-1}(\frac{y}{x})$  
[Examples of the vector argument](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-the-vector-argument)  

#### <ins>Write a vector with the help of the direction angle</ins>  
$\vec{a}=|\vec{a}\times(\frac{cos(arg(\vec{a}))}{sin(arg(\vec{a}))})|$  
[Examples of a vectors written with the help of the direction angle](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-a-vectors-written-with-the-help-of-the-direction-angle)  

#### <ins>Unit vectors</ins>  
The unit vector for $\vec{u}_{\vec{a}}$ is given by:  
$\vec{u}_{\vec{a}}=({x_u \atop y_u})=(\frac{\frac{x}{\sqrt{x^2+y^2}}}{\frac{y}{\sqrt{x^2+y^2}}})$  
[Examples of the unit vector](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-the-unit-vector)  

#### <ins>Angle between two vectors</ins>  
$cos(v)=\frac{({x_1\atop y_1})\cdot ({x_2 \atop y_2})}{|({x_1 \atop y_1})|\times|({x_2 \atop y_2})|}=\frac{x_1\times x_2+y_1\times y_2}{\sqrt{(x_1^2+y_1^2)\times(x_2^2+y_2^2)}}$  
[Examples of the angle between two vectors](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-the-angle-between-two-vectors)  

#### <ins>Rotation matrix/Tværvektor</ins>  
Notation: $\hat{\vec{a}}$  
$\hat{\vec{a}}=({-y \atop x})$  
Properties/rules of a rotation matrix:  
$\vec{a}\cdot\vec{b}=\hat{\vec{a}}\cdot \hat{\vec{b}}$  
$\hat{\vec{a}+\vec{b}}=\hat{\vec{a}}+ \hat{\vec{b}}$  
$\hat{\vec{a}}\cdot \vec{b}=-\vec{a}\cdot \hat{\vec{b}}$  
$\hat{\hat{\vec{a}}}=\vec{a}$  
[Exapmles of the rotation matrix](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#exapmles-of-the-rotation-matrix)

#### <ins>Determinant</ins>  
$det(\vec{a},\vec{b})=\hat{\vec{a}}\cdot \vec{b}=|{x_1 x_2 \atop y_1 y_2}| = x_1\times y_2-y_1\times x_2=|\vec{a}|\times |\vec{b}|\times sin(v)$  
[Examples of the determinant](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-the-determinant)  

#### <ins>Orthogonal and parallel actual vectors</ins>  
[Examples of an orthogonal and parallel actual vector](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-an-orthogonal-and-parallel-actual-vector)  

#### <ins>Projection of a vector on another vector</ins>  
[Examples of a projection of a vector on another vector](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-a-projection-of-a-vector-on-another-vector)
