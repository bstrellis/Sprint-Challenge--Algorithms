Add your answers to the questions below.

1. What is the runtime complexity of your `heapsort` function? (If you used any
   Python built-in functions, you can find their time complexities here:
   https://wiki.python.org/moin/TimeComplexity )

   Other hints, to save you some searching:

   * Heap insert: `O(log n)`
   * Heap delete: `O(log n)`
   * Heap get max: `O(1)`

******
   O(n) because the 'for' and 'while' loops are both O(n)

2. Could one make your algorithm run in better time? If so, how? If not, why
   not?

******
   I'm virtually certain that a computer scientist could make it run in better time, but I myself do not see a way to improve it at this moment.

3. What is the space complexity of your `heapsort` function? Recall that your
   implementation should return a new array with the sorted data. (Also remember
   that the size of the input array passed to the `heapsort()` function does
   _not_ contribute to the size complexity.)

   Most online sources say that the space complexity of heapsort is `O(1)`. What
   would we have to change in our code to get there?

   Space complexity of my function is O(n) because I use a list ('sortedArr') outside of my heap. Not sure what I'd have to change to get to O(1).