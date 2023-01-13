# About this Course

In this course on Linear Algebra we look at what linear algebra is and how it relates to vectors and matrices. Then we look through what vectors and matrices are and how to work with them, including the knotty problem of eigenvalues and eigenvectors, and how to use these to solve problems. Finally  we look at how to use these to do fun things with datasets - like how to rotate images of faces and how to extract eigenvectors to look at how the Pagerank algorithm works.

Since we're aiming at data-driven applications, we'll be implementing some of these ideas in code, not just on pencil and paper. Towards the end of the course, you'll write code blocks and encounter Jupyter notebooks in Python, but don't worry, these will be quite short, focussed on the concepts, and will guide you through if you’ve not coded before.

At the end of this course you will have an intuitive understanding of vectors and matrices that will help you bridge the gap into linear algebra problems, and how to apply these concepts to machine learning.

![Linear Algebra](https://user-images.githubusercontent.com/76781033/212262943-f223452a-6587-4826-9332-884c8b36d4e3.jpg)
# Week 1: Introduction to Linear Algebra and Mathematics for Machine Learning

In this first module we look at how linear algebra is relevant to machine learning and data science. Then we'll wind up the module with an initial introduction to vectors. Throughout, we're focussing on developing your mathematical intuition, not of crunching through algebra or doing long pen-and-paper examples. For many of these operations, there are callable functions in Python that can do the adding up - the point is to appreciate what they do and how they work so that, when things go wrong or there are special cases, you can understand why and what to do.

## Objectives
- Recall how machine learning and vectors and matrices are related
- Interpret how changes in the model parameters affect the quality of the fit to the training data
- Recognize that variations in the model parameters are vectors on the response surface - that vectors are a generic concept not limited to a physical real space
- Use substitution / elimination to solve a fairly easy linear algebra problem
- Understand how to add vectors and multiply by a scalar number

# Week 2: Vectors are Objects that move around space

In this module, we look at operations we can do with vectors - finding the modulus (size), angle between vectors (dot or inner product) and projections of one vector onto another. We can then examine how the entries describing a vector will depend on what vectors we use to define the axes - the basis. That will then let us determine whether a proposed set of basis vectors are what's called 'linearly independent.' This will complete our examination of vectors, allowing us to move on to matrices in module 3 and then start to solve linear algebra problems.

## Objectives

- Calculate basic operations (dot product, modulus, negation) on vectors
- Calculate a change of basis
- Recall linear independence
- Identify a linearly independent basis and relate this to the dimensionality of the space

# Week 3: Matrices: Objects that Operate on Vectors

Now that we've looked at vectors, we can turn to matrices. First we look at how to use matrices as tools to solve linear algebra problems, and as objects that transform vectors. Then we look at how to solve systems of linear equations using matrices, which will then take us on to look at inverse matrices and determinants, and to think about what the determinant really is, intuitively speaking. Finally, we'll look at cases of special matrices that mean that the determinant is zero or where the matrix isn't invertible - cases where algorithms that need to invert a matrix will fail.

## Objectives

- Understand what a matrix is and how it corresponds to a transformation.
- Explain and calculate inverse and determinant of matrices
- Identify and explain how to find inverses computationally and what goes wrong.

# Week 4: Matrices make Linear Mappings

In Module 4, we continue our discussion of matrices; first we think about how to code up matrix multiplication and matrix operations using the Einstein Summation Convention, which is a widely used notation in more advanced linear algebra courses. Then, we look at how matrices can transform a description of a vector from one basis (set of axes) to another. This will allow us to, for example, figure out how to apply a reflection to an image and manipulate images. We'll also look at how to construct a convenient basis vector set in order to do such transformations. Then, we'll write some code to do these transformations and apply this work computationally.

## Objectives

- Identify matrices as operators
- Relate the transformation matrix to a set of new basis vectors
- Formulate code for mappings based on these transformation matrices
- Write code to find an orthonormal basis set computationally

# Week 5: Eigenvalues and Eigenvectors

Eigenvectors are particular vectors that are unrotated by a transformation matrix, and eigenvalues are the amount by which the eigenvectors are stretched. These special 'eigen-things' are very useful in linear algebra and will let us examine Google's famous PageRank algorithm for presenting web search results. Then we'll apply this in code, which will wrap up the course.

## Objectives

- Identify geometrically what an eigenvector/value is
- Apply mathematical formulation in simple cases
- Build an intuition of larger dimention eigensystems
- Write code to solve a large dimentional eigen problem




