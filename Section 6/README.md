# Section 6: Matrix rank

Matrix rank 

# What I Learned


### Chapter 62. Rank: concept, terms, and application

- Terminology `r` or `rank(A)`
    - Non-negative integer (0,1,2,3 ...) 
        - Connected to dimensionality of information contained in matrix

<img src="maxiumRankOfmatrix.JPG" alt="alt text" width="300"/>

- Finding maximum possible rank, is to count of 1. **rows** and 2.**columns** and then take smaller of those two 
    - It cannot be larger than maximum r, it can only be smaller


<img src="formalDefinationOfRank.jpg" alt="alt text" width="400"/>

- **Rank** tai aste
- **Rank** is concept of whole matrix, not connected to specific **columns** of matrix or **rows** of matrix
    - `rank(C(A))` does not exist
    - `rank(R(A))`
    does not exist
        - Instead use `rank(A)`, one rank of matrix!

- Some terminology

<img src="rankTerminology.JPG" alt="alt text" width="500"/>

<img src="rankTerminology2.JPG" alt="alt text" width="500"/>

<img src="dimensionalityOfInformation.JPG" alt="alt text" width="400"/>


- Geometrically speaking, plotting each column as vector into 2d plane. We can see that other columns are not providing any additional unique information, so **RANK** is **two**
    - We could express all these point using **two** vectors

<img src="maxiumRankOfmatrix2.JPG" alt="alt text" width="400"/>

- We can plot this 2x3 matrix in 2-dimensional plane as seen in **1.**


- Plotting this into **R^3**
    - **Rank** could be different if we plot this using rows, not the case, but want to illustrate
- As you can see from point **2.** Plane plotted in 3-dimension as such. It's still **2-dimensional subspace** plane inside 3-dimensions
    - This would still give us **Rank** of two, coz its property of an matrix

<img src="oneDefinationForMatrixRank.JPG" alt="alt text" width="400"/>

- Summary of rank

<img src="rankSummary.JPG" alt="alt text" width="500"/>

- Matrix Rank has some applications
    - Can be used if matrix has inverse
        - Only full rank matrices has inverse
    - Used also many other places, such as vector analysis
        - Used to determine how much information is contained in multivariant dataset
        - Data compression and so on

### Chapter 63. Computing rank: theory and practice





## Some additional sources

- [Rank](https://www.youtube.com/watch?v=uQhTuRlWMxw)
