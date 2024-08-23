# saniyachatterjee-EXP-8
## AIM
To study and implement C++ 2D array matrices
## THEORY
The theory behind 2D array matrices in C++ centers on organizing data into a grid structure with rows and columns, which allows for efficient access and manipulation. A 2D array can be thought of as an array of arrays, where each element is accessed using a pair of indices, (i, j), representing its row and column positions. In memory, these arrays are stored in contiguous blocks, following a row-major order, meaning that elements are stored row by row. This layout affects how quickly and efficiently data can be accessed and modified.

Operations on 2D arrays include traversal (iterating through elements), addition or subtraction of matrices by combining corresponding elements, and multiplication which involves summing products of rows and columns from two matrices. <br>Transposing a matrix involves flipping it over its diagonal, effectively swapping rows and columns.

Dynamic allocation allows for flexible handling of matrices when their size is not known at compile time. By using pointers and memory management techniques, C++ enables the creation and manipulation of 2D arrays whose dimensions can be determined during runtime.

While 2D arrays offer simplicity and direct indexing, they have limitations such as fixed size constraints and the potential for manual memory management errors. To overcome these limitations and enhance functionality, standard libraries like std::vector or specialized libraries like Eigen can be employed. These theoretical foundations are essential for applying 2D arrays in practical contexts such as mathematical computations, computer graphics, and data analysis.
```
//Name: Saniya Chatterjee
//Prn: 23070123113
//Class: EnTC B-2
#include <iostream>
using namespace std;

int main() {
    int temp[3][3], i, j,k,l;
    for (i=0 ; i<3 ; i++){
        for (j=0;j<3;j++){
            cout<<" Enter element-("<<i<<j<<"):";
            cin>>temp[i][j];
        }
    }
    for(k-0; k<3; k++){
        for (l=0;l<3;l++){
            cout<<temp[k][l];
            cout<<" ";
    }
    cout <<endl;
    }
}
```
