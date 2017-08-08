# Big O Assessment

 ### O Boy! It's time to evaluate your understanding of Big O Notation!

 ##

  PART ONE: Please answer the following questions:

 1. Describe the purpose of Big 0.

    > Big O is a way of quantifying the time efficiency of a function in its worst case scenario.

---


 2. What 2 things does it measure?

    > Time and space

---


 3. Which of the following shows Big O time complexity in order?

    a) O(1), O(n log n), O(log n), O(n), O(n^2)

    b) O(1), O(log n), O(n), O(n log n), O(n^2)

    c) O(1), O(log n), O(n log n), O(n), O(n^2)

    > b!

---



4. Which of these algorithm(s) run in O(log n) time?

   Binary Search

   Bubble Sort

   Quick Sort (average case)

   Linear Search

   > Binary Search

---



5. Select the best time complexity that even the most efficient sort algorithm can have.

    O(log n)

    O(n log n)

    O(n)

    O(n^2)

    > O(log n)

---


 6. Describe what sets these these 3 complexities apart from each other: O(1), O(n) and O(n^2)

    > O(1) is constant time, this means that it has a consistent action and times that it performs that action.

    > O(n) is linear time which takes a consistently incrementing amount of time based upon the length or size of it's input.

    > O(n^2) is quadratic time which takes n^2 time based upon two time and or length based actions.

---


7. How would you recognize O(log n) and O(n log n) time complexities in a function?

    > O(log n) would be any function that halves n every time it performs it's action.

    > O(n log n) is like O(log n) and O(n) combined. Think of a for loop and a sorting function combined.

---

  ##

  PART TWO: In a new file, write examples of algorithms/functions for each of the Big O complexities below.
    Upload your file to your repository when complete and submit in Learn --> Exercises.

    1. O(1)

    function(){
      for(i = 0; i < 10; i++){
        console.log(i);
      }
    }

    2. O(n)

    function(arr){
      for(i = 0; i < arr.length; i++){
        console.log(arr[i]);
      }
    }

    3. O(n^2)

    function(arr){
      for(i = 0; i < arr.length; i++){
        for(j = 0; j < arr[i].length; j++){
          console.log(arr[i][j]);
        }
      }
    }
