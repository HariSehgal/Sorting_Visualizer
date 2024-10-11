# Sorting Visualizer

## Project Overview
Sorting Visualizer is a C++ project that visually demonstrates the functionality of various sorting algorithms, including Bubble Sort, Insertion Sort, Selection Sort, Heap Sort, Merge Sort, and Quick Sort. The project uses the SDL2 library for rendering graphical representations of the sorting process, providing a hands-on learning experience for understanding how these algorithms work in real-time.

## Features
- Visual representation of popular sorting algorithms.
- Interactive user interface within the terminal of VS Code.
- Step-by-step visualization of sorting operations.
- Algorithm Selector and Program Exit options integrated into the UI.

## Sorting Algorithms Implemented
- **Bubble Sort**: A simple comparison-based algorithm that repeatedly swaps adjacent elements if they are in the wrong order.
- **Insertion Sort**: Builds the sorted array one element at a time by inserting each element into its correct position.
- **Selection Sort**: Repeatedly selects the smallest unsorted element and moves it to the beginning of the array.
- **Heap Sort**: Converts the array into a heap structure, then extracts the largest element and rebuilds the heap.
- **Merge Sort**: Recursively divides the array into halves, sorts them, and merges them back together.
- **Quick Sort**: Partitions the array around a pivot element and recursively sorts the left and right partitions.

## Environment Setup
To run this project, the following tools and libraries are required:
- **C++**: The core programming language used for implementing the algorithms.
- **MinGW**: A C++ compiler used for compiling the code (Windows users).
- **Visual Studio Code**: The integrated development environment (IDE) used for writing and running the code.
- **SDL2 Library**: The Simple DirectMedia Layer (SDL2) library is used for rendering the graphical output of the sorting process.

## How to Run
1. **Clone the Repository**:  
   git clone https://github.com/HariSehgal/Sorting_Visualizer.git
2. **Install SDL2**:  
   Download and set up the SDL2 library for your system. Ensure that the SDL2 headers and binaries are linked to the project.
3. **Compile the Project**:  
   Use the MinGW compiler (or equivalent) to compile the C++ code. Open a terminal and run:
   g++ -o sorting_visualizer main.cpp -lmingw32 -lSDL2main -lSDL2
4. **Run the Executable**:  
   Once compiled, run the generated executable:
   ./sorting_visualizer
5. **Use the Interface**:  
   Select a sorting algorithm from the terminal UI and observe the sorting process visualized in real-time.

## Control Handling
- **Algorithm Selector**: Choose from the available sorting algorithms to begin sorting.
- **Exit Program**: Select this option to close the visualizer.

## Project Structure
- main.cpp: Core logic and algorithm implementation.
- SDL2: Header files and dependencies for rendering visual output.
- README.md: Documentation for the project.
- CMakeLists.txt: Configuration for building the project using CMake.

## Future Improvements
- Add the ability to adjust array size.
- Add option to compare different sorting algorithms simultaneously.
- Implement additional sorting algorithms like Radix Sort, Shell Sort, etc.

## Acknowledgments
This project was developed as part of a summer training program in **Data Structures and Algorithms** using 
C++ at **Coding Blocks**. Special thanks to our mentor, **Mayank Jha**, for his guidance and support throughout the project.

This **README** provides a comprehensive overview of the project, its setup, usage instructions, and future improvements. Let me know if you need any further customization!