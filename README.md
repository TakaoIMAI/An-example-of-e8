# Digitalization of exceptional simple Lie algebras
 We publish (1)the digitalized 248 bases of the 248x248 matrix of r8C by using Maxima's function: matrix. 
These digitalized matrices are the result of the following Paper:

Digitalization of exceptional simple Lie algebras into matrices over complex numbers
(arXiv:2010.06696v3 [math.RT] 9 Apr 2022)

 Using these digitalized data, Lie bracket operations of exceptional Lie algebras are performed as matrix calculations in the same way as classical Lie algebras.
Computer algebra systems are useful for explicitly calculating high-dimensional Lie algebras.

The programming codes have following 6 contens. With the programming codes,
readers can simulate the process of digitalization and verify the proof of this paper.

(1)Operations (see Section 1 ) of the Cayley algebra and the Jordan algebra by using Maxima.

(2)Lie bracket operations of R4, R6, R7, and R8 by using Maxima.

(3)Convertes from ad(R8C) over the Cayley algebra to the matrix of r8C , by using Maxima for performing mathematical operation and using the programming
language Python for string conversion.

(4)Check the Lie bracket operations as matrix calculations of r4C , r6C , r7C , and r8C and confrming these root systems.

(5)Decompose an element of r8C into a linear combination of the 248 bases matrices.

(6)Check the Lie bracket operations of Lie subalgebras of r8C

# Verup 2023/10/30
Fixed the incorrect maximum_tempdir in ../Operation_and_Converter/wxMaxima/1st_step.mac and 2nd_step.mac.
An error occurred because there was no Relement.txt file in ../Operation_and_Converter/wxMaxima/elements def.mac. Prepared Relement.txt. 
Also fixed the incorrect stfile and tempdir settings in elements_def.mac.
