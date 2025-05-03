# Linear Algebra

What even is it, why would anyone care, and how should it be taught, if indeed it should be at all?


---

## Notes on conceptualization

 * Linear Algebra as the math of multiple dimensions: position relative to other topics (algebra, calculus/analysis, multivariate calculus, more?) and applications (physics, etc.)
     * something about not being proof-oriented: reason to learn linear algebra: using it, vs. developing it mathematically/doing proofs (Do you really need "mathematical sophistication"?)

 * things to repeat for numbers, vectors, matrices:
     * duality between data and function/transform
         * Transform view: where the output can be
         * Data view: where the points are
     * order doesn't matter, as long as consistent (for vectors/matricies)
         * Andrew Ng mentions row VS column matrices decision in [batch 256](https://www.deeplearning.ai/the-batch/issue-256/)

 * Transform a problem into a matrix problem
 * Can it be solved?
     * Analogy with zero: Is this matrix like zero? (Can we divide by it and get a unique answer?)

Lots of re-expression and reduced echelon form etc. stuff: Can we move toward a solution by multiplying by invertible things?

> "row echelon form" isn't a "form" of the matrix! It's the matrix times some other nonsense! ><
> what lies are we teaching the children!?

Dimensions are degrees of freedom


---

## Existing things about Linear Algebra

### By me

 * [A brief development of matrix multiplication](https://planspace.org/20240624-brief_development_matrix_multiplication/)
 * [The flow metaphor for matrix multiplication](https://planspace.org/20210915-flow_metaphor_for_matrix_multiplication/)

### More looked at by me

 * [Linear Algebra Done Right, 4th ed.](https://linear.axler.net/) (Sheldon Axler)
     * sort of an expansion of his 1995 [Down with Determinants!](https://www.axler.net/DwD.html)
     * [my post](https://planspace.org/20240616-linear_algebra_done_right/)
 * [Linear Algebra for Everyone](https://math.mit.edu/~gs/everyone/) (Gilbert Strang, 2020)
     * [notes](lafe/)
 * [3Blue1Brown](https://www.3blue1brown.com/) on [linear algebra](https://www.3blue1brown.com/topics/linear-algebra)
 * [Vector](https://press.uchicago.edu/ucp/books/book/chicago/V/bo213793784.html): A Surprising Story of Space, Time, and Mathematical Transformation (Robyn Arianrhod, 2024)

### Not very looked at by me

 * [Linear algebra, 3rd ed.](https://link.springer.com/book/10.1007/978-1-4757-1949-9) (Serge Lang, 1987)
     * "There are other great books out there that I use in the background as well. One of my favorites is the Serge Lang book that is simply called, "Linear Algebra.".  I would say that most people who teach or are interested in Linear Algebra know of this classic book." (Michael "Mike" Curry, at Bunker Hill Community College)
 * [Elementary Linear Algebra, 8th ed.]() (Ron Larson, 2016)
     * Cengage textbook used at Bunker Hill Community College, "chosen by the BHCC math department," studied by 
David Cerna.
 * [The Theory of Matrices](https://webhomes.maths.ed.ac.uk/~v1ranick/papers/gantmacher1.pdf) (F. R. Gantmacher, 1959)
     * This was [linked](https://x.com/predict_addict/status/1892590757699002844) by [Valeriy M.](https://x.com/predict_addict) as "The Holy Grail of forbidden knowledge about matrices' math." (She also maintains [Awesome_Math_Books](https://github.com/valeman/Awesome_Math_Books), where both volumes one and two are listed with _five_ fire emojis.
