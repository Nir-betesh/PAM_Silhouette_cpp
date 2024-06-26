# PAM & Silhouette Algorithm Implementation (C++)
This project implements the PAM (Partitioning Around Medoids) and Silhouette algorithms efficiently using C++.
These algorithms are widely used in cluster analysis to determine the optimal number of clusters in a dataset.

# Features
* Efficient Implementation: The algorithms are implemented in C++ to ensure high performance and scalability.
* Utilization of Special Features of Registers: Special features of registers are utilized to optimize the execution time, especially for large input matrices.
#
* Input: The code takes a distance matrix of size N x N as input.
* Output: The output of the code is the optimal number of clusters determined by the algorithms.

# Usage
To run the code, follow these steps:
1. Clone Repository: Clone this repository to your local machine using the following command:
```
git clone https://github.com/Nir-betesh/PAM_Silhouette_cpp.git
```

3. Open Solution in Visual Studio: Navigate to the project folder and open the pam_prog_lang.sln solution file using Visual Studio.
4. Build Solution: Build the solution by selecting Build > Build Solution from the Visual Studio menu. Alternatively, you can use the shortcut Ctrl+Shift+B.
5. Run Application: After successfully building the solution, you can run the application by selecting Debug > Start Without Debugging from the menu, or by pressing Ctrl+F5.

# Results
* The implementation has been tested with various input sizes, including a distance matrix of size 10,000 x 10,000.
* The results demonstrate successful and efficient clustering with this large input size.
* The running time for processing the 10,000 x 10,000 distance matrix is approximately 11.405 seconds.

# Requirements
* Visual Studio (or any compatible C++ IDE)
* C++ compiler (e.g., MSVC)
* Standard Template Library (STL)

# Authors
* Almog Khaikin
* Nir Betesh
