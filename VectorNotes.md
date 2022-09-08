# **Vector2D Cheat Sheet**
#### <ins>Vectors</ins>  
A vector is an arrow with a lenght and a direction.  
$\vec{a}$  
A vector contains two coordinates describing how long the vector is in the direction of the x and the y axis.  
$\vec{a}=({a_1 \atop a_2})$  
When drawing a vector into your coordinate system, it does not matter where you start, as long as the arrow has the same length and direction.  
[Examples of plotting vectors into your coordinate system](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-plotting-vectors-into-your-coordinate-system)

#### <ins>Addition of vectors</ins>  
$\vec{a}+\vec{b}=({a_1 + a_2 \atop b_1 + b_2})$  
Properties/rules of vector adding: 
- $\vec{a}+\vec{b}=\vec{b}+\vec{a}$
- $\vec{a}+\vec{0}=\vec{a}$
- $k(\vec{a}+\vec{b})=k\vec{a}+k\vec{b}$
- $\vec{a}+(\vec{b}+\vec{c})+\vec{c}$  
[Examples of vector adding](https://github.com/RasmussenTobias/Vector2DCheatSheet/blob/main/Examples.md#examples-of-vector-adding)  

#### <ins>Subtraction of vectors</ins>  
$\vec{a}-\vec{b}=({a_1-b_1 \atop a_2-b_2})$  

#### <ins>Multiply constant onto vector</ins>  
$k\times ({x \atop y})=({k\times x \atop k\times y})$  

#### <ins>Dot product</ins>  
$({x_1 \atop y_1})\cdot({x_2 \atop y_2})=x_1\times x_2 + y_1 \times y_2$  

#### <ins>Length of a vector</ins>  
$|\vec{a}|=\sqrt{x^2+y^2}$  
Properties/rules of the lenght of a vector:  
$|k\times \vec{a}|=k\times |\vec{a}|$  
$|\vec{a}|^2=\vec{a}\cdot\vec{a}$

#### <ins>Vector argument</ins>  
$arg(\vec{a})=sin^{-1}(\frac{y}{\sqrt{x^2+y^2}})$ $=cos^{-1}(\frac{x}{\sqrt{x^2+y^2}})=tan^{-1}(\frac{y}{x})$

#### <ins>Write a vector with the help of the direction angle</ins>  
$\vec{a}=|\vec{a}\times(\frac{cos(arg(\vec{a}))}{sin(arg(\vec{a}))})|$

#### <ins>Unit vectors</ins>  
The unit vector for $\vec{u}_{\vec{a}}$ is given by:  

$\vec{u}_{\vec{a}}=({x_u \atop y_u})=(\frac{\frac{x}{\sqrt{x^2+y^2}}}{\frac{y}{\sqrt{x^2+y^2}}})$  
#### <ins>Angle between two vectors</ins>  
$cos(v)=\frac{({x_1\atop y_1})\cdot ({x_2 \atop y_2})}{|({x_1 \atop y_1})|\times|({x_2 \atop y_2})|}=\frac{x_1\times x_2+y_1\times y_2}{\sqrt{(x_1^2+y_1^2)\times(x_2^2+y_2^2)}}$

#### <ins> </ins>

#### <ins> </ins>

#### <ins> </ins>

#### <ins> </ins>

#### <ins> </ins>
