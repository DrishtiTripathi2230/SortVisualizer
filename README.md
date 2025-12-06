# Sorting Visualizer

A simple web-based **Sorting Visualizer** that demonstrates different sorting algorithms using animated bars. Users can generate random arrays and visualize how sorting algorithms work step by step.

## Features

- Generate a random array of numbers (visualized as vertical bars)
- Visualize multiple sorting algorithms:
  - **Bubble Sort**
  - **Insertion Sort**
  - **Selection Sort**
- Animated comparisons and swaps for better understanding
- Interactive buttons to control sorting and array generation

## How to Use

1. **Open `index.html` in your browser**  
   No server or installation required; it works directly in any modern browser.

2. **Generate an Array**  
   Click the "Generate Array" button to create a new random array.

3. **Sort the Array**  
   Click any of the sorting algorithm buttons to see the sorting process:
   - **Bubble Sort**
   - **Insertion Sort**
   - **Selection Sort**

## How It Works

- Each number in the array is represented as a vertical bar.
- Sorting algorithms compare and swap bars based on their height.
- Different colors indicate current comparisons and swaps:
  - **Red** → Bars being compared
  - **Orange** → Current bar in focus for sorting
  - **Skyblue** → Default color

## Code Structure

- `index.html` – Main HTML file containing UI and script
- `<script>` section includes:
  - `generateArray()` – Generates random bars
  - `bubbleSort()` – Bubble Sort implementation
  - `insertionSort()` – Insertion Sort implementation
  - `selectionSort()` – Selection Sort implementation
- Styling is applied directly via JavaScript for simplicity

## Technologies Used

- **HTML** – Structure of the page
- **CSS (inline)** – Bar styling
- **JavaScript** – Sorting logic and animations
- **Async/await** – To animate the sorting process

## Future Improvements

- Add **Quick Sort** and **Merge Sort** visualizations
- Add **speed control slider** to adjust animation speed
- Make it **responsive for mobile devices**
- Add **color legend** for better understanding

## Demo
Generate Array


<img width="1905" height="472" alt="image" src="https://github.com/user-attachments/assets/68356ffc-4687-4d18-9fc7-82afcba42ddb" />

working(sorting):


<img width="1903" height="538" alt="image" src="https://github.com/user-attachments/assets/362dc209-078b-41f1-b4fb-dd07f616851a" />


after sorting:


<img width="1648" height="504" alt="image" src="https://github.com/user-attachments/assets/245f0663-ac46-468b-891a-049ed402c3fd" />


## License

This project is open-source and free to use.

