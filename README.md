# 0x1B. C - Sorting algorithms & Big O

## Resources:books:
Read or watch:
* [Big-O Algorithm Complexity Cheat](https://www.bigocheatsheet.com/)
* [Big O Notation - Ruby Reilly](https://medium.com/@rubyclaroreilly/big-o-notation-f2c0d0e60888)
* [Big O Notation: A primer for beginning devs](https://www.educative.io/blog/a-big-o-primer-for-beginning-devs?aid=5082902844932096&utm_source=google&utm_medium=cpc&utm_campaign=blog-dynamic&gclid=EAIaIQobChMIlb2ol-H36QIVTwiICR38HQ-LEAAYASAAEgJjGPD_BwE%3E)
* [Complete Beginner's Guide to Big O Notation](https://www.youtube.com/watch?v=kS_gr2_-ws8)
* [Data Structures - Asymptotic Analysis](https://www.tutorialspoint.com/data_structures_algorithms/asymptotic_analysis.htm)
* [RANDOM.ORG - Integer Set Generator](https://www.random.org/integer-sets/)
* [Sorting algorithm](https://en.wikipedia.org/wiki/Sorting_algorithm#Classification)
* [algorithm - What is a plain English explanation of "Big O" notation?](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation)
* [What is the time complexity of indexing, inserting and removing from common data structures?](https://stackoverflow.com/questions/122799/what-is-the-time-complexity-of-indexing-inserting-and-removing-from-common-data)
* [Sorting Algorithms Animations](https://www.toptal.com/developers/sorting-algorithms)
* [Sorting Algorithms BigPicture](https://www.youtube.com/watch?v=RLuBLU_NgaA)
* [algoritmos de ordenamiento](https://www.youtube.com/results?search_query=algoritmos+de+ordenamiento)
* [ALGORITMOS - METODOS DE ORDENAMIENTO](https://www.youtube.com/watch?v=VJ_EUuURRg4)
* [¿Qué es la complejidad algorítmica y con qué se come?](https://medium.com/@joseguillermo_/qu%C3%A9-es-la-complejidad-algor%C3%ADtmica-y-con-qu%C3%A9-se-come-2638e7fd9e8c)
* [Big O notation](https://en.wikipedia.org/wiki/Big_O_notation)
* [Análisis de la complejidad de los algoritmos](https://www.cs.us.es/~jalonso/cursos/i1m/temas/tema-28.html)
* [Rendimiento de algoritmos y notación Big-O](https://www.campusmvp.es/recursos/post/Rendimiento-de-algoritmos-y-notacion-Big-O.aspx)
* [Big-O is easy to calculate, if you know how](https://justin.abrah.ms/computer-science/how-to-calculate-big-o.html)
* [8 time complexities that every programmer should know](https://adrianmejia.com/most-popular-algorithms-time-complexity-every-programmer-should-know-free-online-tutorial-course/#Binary-search)

---

# Sorting Algorithms and Big O Analysis

In this repository, you will find implementations of various sorting algorithms in the C programming language. Additionally, we provide an analysis of the time complexity (Big O notation) for each sorting algorithm.

## Sorting Algorithms Included

1. **Bubble Sort:** A simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

2. **Selection Sort:** This algorithm divides the input list into a sorted and an unsorted region, and it repeatedly selects the smallest (or largest) element from the unsorted region and moves it to the end of the sorted region.

3. **Insertion Sort:** This algorithm builds a sorted list one element at a time by repeatedly removing elements from the input data and inserting them into their correct position in the sorted list.

4. **Merge Sort:** An efficient, divide-and-conquer algorithm that divides the input array into two halves, recursively sorts them, and then merges the sorted halves to produce the final sorted array.

5. **Quick Sort:** Another efficient, divide-and-conquer algorithm that selects a pivot element from the array and partitions the other elements into two sub-arrays according to whether they are less than or greater than the pivot. The sub-arrays are then recursively sorted.

---
## Learning Objectives:bulb:
What you should learn from this project:

* At least four different sorting algorithms
* What is the Big O notation, and how to evaluate the time complexity of an algorithm
* How to select the best sorting algorithm for a given input
* What is a stable sorting algorithm

---

### [0. Bubble sort](./0-bubble_sort.c)
* Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm


### [1. Insertion sort](./1-insertion_sort_list.c)
* Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm


### [2. Selection sort](./2-selection_sort.c)
* Write a function that sorts an array of integers in ascending order using the Selection sort algorithm


### [3. Quick sort](./3-quick_sort.c)
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm


### [4. Shell sort - Knuth Sequence](./100-shell_sort.c)
* Write a function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence


### [5. Cocktail shaker sort](./101-cocktail_sort_list.c)
* Write a function that sorts a doubly linked list of integers in ascending order using the Cocktail shaker sort algorithm


### [6. Counting sort](./102-counting_sort.c)
* Write a function that sorts an array of integers in ascending order using the Counting sort algorithm


### [7. Merge sort](./103-merge_sort.c)
* Write a function that sorts an array of integers in ascending order using the Merge sort algorithm


### [8. Heap sort ](./104-heap_sort.c)
* Write a function that sorts an array of integers in ascending order using the Heap sort algorithm


### [9. Radix sort](./105-radix_sort.c)
* Write a function that sorts an array of integers in ascending order using the Radix sort algorithm


### [10. Bitonic sort](./106-bitonic_sort.c)
* Write a function that sorts an array of integers in ascending order using the Bitonic sort algorithm


### [11. Quick Sort - Hoare Partition scheme](./107-quick_sort_hoare.c)
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm


### [12. Dealer](./1000-sort_deck.c)
* Write a function that sorts a deck of cards.

---

## Usage

To use the sorting algorithms provided in this repository, follow these steps:

1. Clone the repository to your local machine.

```bash
git clone https://github.com/yourusername/sorting-algorithms.git
```

2. Navigate to the project directory.

```bash
cd sorting-algorithms
```

3. Compile the C files using your preferred C compiler.

```bash
gcc -o bubble_sort bubble_sort.c
gcc -o selection_sort selection_sort.c
gcc -o insertion_sort insertion_sort.c
gcc -o merge_sort merge_sort.c
gcc -o quick_sort quick_sort.c
```

4. Run the executable for the sorting algorithm you want to test.

```bash
./bubble_sort
./selection_sort
./insertion_sort
./merge_sort
./quick_sort
```

## Big O Analysis

The time complexity of each sorting algorithm has been analyzed and documented in the `BigO_Analysis.md` file. It provides insights into the efficiency of each algorithm in terms of their time complexity as the input size grows.

## Contribution

If you find any bugs, have suggestions, or want to add more sorting algorithms, feel free to contribute to this repository. Simply fork the repository, make your changes, and submit a pull request.

We hope you find this repository useful in understanding sorting algorithms and their time complexity. Happy coding!

## Disclaimer

Please note that this repository is for educational purposes only. While the algorithms are implemented with care, they may not be the most optimized versions for production use. Always consider using standard library functions or well-tested third-party libraries for sorting tasks in real-world applications.
