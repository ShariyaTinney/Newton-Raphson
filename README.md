

📐 Newton-Raphson Method in C++

📌 Overview

✅This project is a simple implementation of the "Newton-Raphson Method" for finding the roots of "nonlinear equations" using "C++".
✅The Newton-Raphson Method is a powerful and widely-used iterative numerical technique for solving equations of the form "f(x) = 0". It uses both the function value and its derivative to converge to the root more rapidly than other methods.
✅>Equation used in this implementation:
>f(x) = x³ - x - 11
>Derivative of f(x):
>f'(x) = 3x² - 1



🎯 Features
✅ Solves nonlinear equations using the "Newton-Raphson Method"
✅ Efficient iterative process that converges quickly
✅ Displays the root and the number of iterations it took to find it
✅ Allows customization of the function and its derivative
✅ Clean and well-commented C++ code


🛠 Requirements
To run this project, you'll need:
* A C++ compilersuch as g++ or clang++
* A C++ IDE (optional), such as VS Code, CLion, Code::Blocks, or any text editor of your choice

  

🚀 How to Run
1. Clone the repository or download the source code:
   git clone https://github.com/YOUR_USERNAME/newton-raphson-method-cpp.git
   cd newton-raphson-method-cpp
  
2. Compile the C++ code:*
   g++ main.cpp -o newtonRaphson
   
3.Run the program:
   ./newtonRaphson

🧠 How It Works
* The Newton-Raphson method uses an initial guess `x0` and iterates to find the root by applying the formula:
  x_i+1 = x_i - f(x_i)/f'(x_i)
  
* The method continues to iterate until the difference between successive guesses is smaller than the specified tolerance (`EPSILON`).
* In each iteration, the function value and its derivative are evaluated, and the new guess `x(i+1)` is updated based on the formula above.
The method converges rapidly if the initial guess is close enough to the actual root.


📁 File Structure
newton-raphson-method-cpp/
├── main.cpp      # Main C++ program implementing the Newton-Raphson Method
└── README.md     # Project documentation (this file)


📤 Sample Output
Running the program with an initial guess x0 = 2 will yield output similar to this:
The value of the root is : 2.080081


 🔧 Customization
You can customize the following:
✅ Modify the function func(x) and its derivative "derivFunc(x)" to solve a different equation.
✅ Change the initial guess x0 to improve convergence for different types of equations.
✅ Adjust the error tolerance (EPSILON) to control the precision of the result.



🤝 Contributions
Contributions are welcome!
To contribute:
* Fork the repository
* Create a new branch
* Submit a pull request with your improvements
If you have any suggestions or encounter issues, please open an "Issue" on the GitHub repository.


📧 Contact
For any questions or feedback, feel free to contact:
"Shaiya Tinney"— \[[shariyatinney.gmail@example.com](mailto:shariyatinney.gmail@example.com)]

>Reminder:
> ✅ Replace Shaiya Tinney in the Git clone URL
> ✅ Replace  "Shaiya Tinney" and "shariyatinney.gmail@example.com" with your actual Shaiya Tinney and shariyatinney.gmail@example.com before publishing.


📚 Resources
* [Newton-Raphson Method – Wikipedia](https://en.wikipedia.org/wiki/Newton%27s_method)
* [Numerical Methods in C++](https://cplusplus.com/)



🧩 Language
![C++](https://img.shields.io/badge/C%2B%2B-100%25-blue)



💡 Future Improvements
* Allow "dynamic input" of the function, its derivative, and initial guess for a more generalized solution.
* Implement a "convergence check" to handle cases where the method does not converge.
* Extend the program to support solving systems of nonlinear equations.


