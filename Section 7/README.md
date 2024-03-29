# Section 7: Matrix spaces

Matrix spaces

# What I Learned


### Chapter 72. Column space of a matrix

<img src="columnSpaceDefination.JPG" alt="alt text" width="300"/>

- **C** column

<img src="columnSpaceExplanation.JPG" alt="alt text" width="300"/>

- 1. Own object**s**
    - In matrix, every object its itself
- 2. Own object! 

<img src="officalDefination.JPG" alt="alt text" width="300"/>

- Official definition for Column Space
    - 1. Set of all vectors which can be retrieved from matrix
    - Suomeksi Sarakkaiden virttämä aliavaruus

<img src="isContained.JPG" alt="alt text" width="300"/>

- Is given vector in column space of this matrix. **2.**
    - 1. With following weighted scalars

<img src="zeroVector.JPG" alt="alt text" width="300"/>

- Zero vector is also included in **Column space** of this matrix


<img src="notContained.JPG" alt="alt text" width="300"/>

- 2. Here you can see plane which does not contain vector A in **Column Space**
    - 1. Geometric illustration as vector pointing out of the plane. Hence, **NOT** not contained in **Column Space** of matrix

    Todo heikki 5:00


### Chapter 75. Null space and left null space of a matrix

<img src="nullSpace.JPG" alt="alt text" width="300"/>

- Idea is to get matrix zero, with not zero matrix. Let's look first this thought scalars

- 1. Idea is to have scalar that makes this equation into zero

<img src="nullSpaceDefination.JPG" alt="alt text" width="300"/>

- 1. With vectors/matrices can we find such combination of **v1** where result is zero-vector
    - This **cannot** be zero vector
        - Answer is yes, **2.**
- 3. We cannot find such vector which makes this equation zero.
    - Zero vector not allowed
    - We say, this matrix does **not** have **null space**

- Official definition goes like such
    - `A:n nulliteetti (nollaantumisluku) on dim N(A).`

<img src="officalDefinationNullspace.JPG" alt="alt text" width="400"/>

- Null space is not just one vector, its is entire subspace

<img src="nullSpaceIsSubSpace.JPG" alt="alt text" width="400"/>

- 1. We use scalar with base vector to present null space


<img src="relationBetweenRankAndNullSpace.JPG" alt="alt text" width="500"/>

1. Matrix with empty **null space**
    - Will have linearly independent columns (lineaarisesti riippumaton tai vapaa)
2. Matrix has dependently set
    - Will have **null space**

3. Has two null space vectors, we could pick not only these base vectors

<img src="additionalDefinationForNullSpace.JPG" alt="alt text" width="500"/>

- Null Space operations 

<img src="NullSpaceDramaticMeaning.JPG" alt="alt text" width="500"/>

- You can think null space, once you get in other action will be futile

<img src="NullSpaceGeometricMeaning.JPG" alt="alt text" width="500"/>

- 1. When **V** is not contained in null space, you can move around

- 2. v is contained inside null space
    - 3. Once operation with null space is done, will get zero vector
- We can use null space in Eigen Decomposition

- Left-null and right-null todo heikki perhdy näihin eri avaruuksiin

## Some additional sources

- [column space and null space](https://www.youtube.com/watch?v=uQhTuRlWMxw&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab&index=7)
