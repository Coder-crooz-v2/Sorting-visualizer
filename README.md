# Sorting Algorithm Visualizer

## Project Overview

The Sorting Algorithm Visualizer is a comprehensive project developed in C++ utilizing the SDL2 library. The primary purpose of this project is to provide a real-time graphical representation of various sorting algorithms. This visual feedback aids in understanding the efficiency and behavior of different sorting techniques.

## Features

### Real-time Visualization

- **Graphical Display:** The visualizer displays sorting processes in real-time, providing an intuitive understanding of how each algorithm manipulates data.
- **Dynamic Updates:** The visualization updates dynamically as the sorting algorithm progresses, highlighting the elements being compared, swapped, or inserted.

### Supported Sorting Algorithms

- **Selection Sort:** Demonstrates the process of repeatedly finding the minimum element from the unsorted part and moving it to the sorted part.
- **Insertion Sort:** Shows how elements are inserted into their correct position within the sorted portion of the array.
- **Bubble Sort:** Visualizes the repetitive swapping of adjacent elements to bubble up the largest element to its correct position.
- **Merge Sort:** Illustrates the divide-and-conquer approach of splitting the array and merging sorted halves.
- **Quick Sort:** Displays the process of partitioning the array and recursively sorting the partitions.
- **Heap Sort:** Depicts the heap construction and sorting process by repeatedly extracting the maximum element.

### User Interaction

- **Keyboard Controls:** Users can interact with the visualizer using keyboard inputs to start different sorting algorithms or generate new randomized lists.
  - **0:** Generate a new randomized list.
  - **1:** Start Selection Sort.
  - **2:** Start Insertion Sort.
  - **3:** Start Bubble Sort.
  - **4:** Start Merge Sort.
  - **5:** Start Quick Sort.
  - **6:** Start Heap Sort.
  - **q:** Exit the visualizer.
- **Event Handling:** The visualizer handles user events efficiently, allowing for seamless transitions between different sorting algorithms and operations.

### Array Management

- **Randomized Array Generation:** The project includes functionality to generate a new randomized list of fixed size (130 elements) within the screen height range.
- **Array Loading:** The initial array can be reset to its original state before starting a new sorting algorithm.

## Implementation Details

### SDL Initialization

- **Initialization:** SDL2 is initialized to set up the window and renderer for graphical display.
- **Window and Renderer Creation:** A window is created with specified dimensions, and an accelerated renderer is used for efficient drawing operations.

### Visualization Function

- **Rendering:** The `visualize` function updates the display, drawing rectangles representing array elements. Different colors are used to indicate the current state of elements being processed by the sorting algorithm.
- **Dynamic Updates:** The function is called frequently during sorting to provide a step-by-step visual update of the sorting process.

### Sorting Algorithms

- **Selection Sort, Insertion Sort, Bubble Sort:** Implemented with visual feedback after each significant operation (e.g., comparisons, swaps).
- **Merge Sort, Quick Sort:** Implemented using recursive approaches, with visual feedback for each merge or partition step.
- **Heap Sort:** Implemented with both heap construction and heap extraction phases visualized.

### Advantages

- **Educational Tool:** The visualizer serves as an excellent educational tool for understanding the inner workings of various sorting algorithms.
- **Intuitive Understanding:** By watching the sorting process unfold, users gain an intuitive grasp of algorithm efficiency and behavior.
- **User-Friendly Interaction:** The use of keyboard controls and real-time visual feedback makes the tool interactive and engaging.

## Conclusion

The Sorting Algorithm Visualizer project combines C++ programming with SDL2 graphical capabilities to create an interactive and educational tool. By providing real-time visual feedback for various sorting algorithms, the project enhances understanding and appreciation of sorting techniques in computer science.
