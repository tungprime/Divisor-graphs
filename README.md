# On divisibility relation graphs

This Git repository contains the code we developed to generate data and conduct experiments on divisibility relation graphs as defined and studied in the following paper 

**[1]** Jonathan L. Merzel,  Jan Minac, Tung T. Nguyen, and Nguyen Duy Tan, *On divisibility relation graphs* (preprint, 2025).

There are two main files, each dealing with different interpration of divisibility relation graphs (see Section 2.1 of the paper for the fact that these definitions are equivalent). 
We refer the readers to the individual files for precise descriptions of their functionality. 

1. A construction of $D_n$ using the factorization of $n$. 
   
2. A construction of $D_n$ using the partially ordered set $S$ defined in Section 2.1. As expected, the code here runs faster as it does not have to deal with factoring large numbers. However, it comes with the cost of being less explicit.  

## Description

Our code utilizes the SageMath 10.4 kernel and the Python library NetworkX. 

## License

This project is licensed under the MIT License.
