# 100 Days Of Code - Log

### Day 0: September 7th, 2020 

**Today's Progress:** First stream, planning out my #100daysofcode schedule, app planning

**Thoughts:** Not a lot of code written, but a lot of system, api, model design for `figure out dinner` app

**Link to work:** [Figure Out Dinner](https://github.com/weklund/figure-out-dinner-app)

### Day 1: September 8th, 2020 

**Today's Progress:** Starting review of [Algorithms Illuminated by Tim Roughgarden](http://www.algorithmsilluminated.org/)

**Thoughts:** Rereading chapter one, created a repo so I can implement algos in the material on python notebooks.  Also thought about `figure out dinner`, maybe I should look into barcode apis as phase two and ingredient detection in a later phase

**Link to work:** [Algo review repo](https://github.com/weklund/algorithms-illuminated-notes)


### Day 2: September 12th, 2020 

**Today's Progress:** 
 * Got local notebook environment working
 * Implemented a working Karatsuba Multiplication solution with recursion from section 1.3 of [Algorithms Illuminated by Tim Roughgarden](http://www.algorithmsilluminated.org/)

**Thoughts:**
* Discovered great content from [Adam](https://adamlearns.com/) who just received multiple offers from FAANG companies, who streamed for 2 straight months for prep 
* Forgot that dividing multiple `int` together in Python 3 makes the answer a float 

**Links:** 
* [Algo review repo](https://github.com/weklund/algorithms-illuminated-notes)
* [Tim Karatsuba Video](https://www.youtube.com/watch?v=JCbZayFr9RE&list=PLEGCF-WLh2RLHqXx6-GZr_w7LgqKDXxN_&index=3)
* [Adam's Interview Prep](https://www.youtube.com/playlist?list=PL4Ayjzb5Bhmd1sof3Ri5yoRlUDvfnmpQ8)
* [Livestreaming your development article](https://adamlearns.com/blog/live-streaming-development)
* [Interview Prep Guide](https://docs.google.com/document/d/1eKirumpmwDWTtKCJKn2HuoQ2NavEfR41whmTyaQcio4/edit#)



### Day 3: September 13th, 2020 

**Today's Progress:** 
 * Started on Grokking the Coding Interview, created a [repo](https://github.com/weklund/patterns-for-coding-questions) for note taking of various patterns
 * Explained the Sliding Window pattern and where it can be used
 * Completed Max Sum of Subarray of Size K problem using Sliding Window

**Thoughts:**
 * It's tough to clean the rust of Python while streaming and reviewing forgotten concepts lol 
 * I need to get better at reading all the code when there's an issue instead of immediately printing to debug.  I'll understand it better when I run through the computations mentally.  

**Links:** 
* [Sliding Window Notebook](https://github.com/weklund/patterns-for-coding-questions/tree/master/sliding-window)

### Day 4: September 14th, 2020

**Yesterday's Accomplishments:**
 * Started Grokking the Coding Interview
 * Relearned the Sliding Window pattern and took good notes
 * Solved the first problem in the series using Sliding Window
 
**Today's Goals:**
 * Remember to read through logic before immediately starting to debug (printing fun)

**Today's Accomplishments:** 
 * Completed Smallest Subarray with a given sum problem using Sliding Window 
 * Did not have to print anything during my debugging, getting better at mentally reviewing buggy code

**Thoughts:**
 * I could have a faster recall on list comprehension
 * Had the meat of the logic correct, but I had incorrectly used the wrong loop structure.  Beat myself up pretty bad about it but I need to remember I'm actually going above and beyond what the course wants.  The real exercises aren't until the 'Problem Challenges' 

**Links:**
[Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/Smallest_subarray_with_a_given_sum.ipynb)

### Day 5: September 15th, 2020

**Yesterday's Accomplishments:**
 * Completed smallest subarray with given sum question
 * Started to read through buggy code without immediately printing all the things
 
**Today's Goals:**
 * Remember to read through logic before immediately starting to debug (printing fun) (again)
 * Try to implement the optimal solution without looking

**Today's Accomplishments:** 
 * Completed longest substring with k distinct characters
 * Learned a more elegant way to compare my traversals from watchers

**Thoughts:**
 * Still need to get better at designing the whole solution before writing any code
    - markdown notes as the solution?
    - pseudocode more?
 * Slowly getting better at not printing all the things
 * Refactor all notebooks to use left/right instead of window_start_location/window_end_location

**Links:**
[Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/longest_substring_with_k_distinct_characters.ipynb)

Someone also mentioned I should look at:
[AlgoExpert](https://www.algoexpert.io/product)


### Day 6: September 17th, 2020

**Yesterday's Accomplishments:**
 * Completed longest substring of k distinct characters
 * Used more elegant unique string selection for comparsion
 
**Today's Goals:**
 * Remember to read through logic before immediately starting to debug (printing fun) (again)
 * Try to implement the optimal solution without looking
 * Come up with the whole design for the solution before writing any code

**Today's Accomplishments:** 
 * Biggest goal met was designing the entire logic for the naive solution without writing a single line of code
 * Completed fruit basket problem
 * Was able to recall the entire solution from memory from longest substring of k distinct characters

**Thoughts:**
 * Get feedback on my solution design / pseudocode ish.  Was it too iterative?
 * I gave up too quickly on the solution.  
 * NOTE: It is mentioned in the course content that this is the same problem space as the previous problem, longest substring with k distinct characters
   
   THIS IS NOT TRUE. The constraints in this problem require you to keep track of the characters to know which ones have been picked and need to be dropped off.
   
   The previous problem was only measuring contiguous unique characters. This led me down the wrong optimization path.

**Links:**
 [Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/fruits_into_baskets.ipynb)
 
 ### Day 7: September 18th, 2020
 
 **Yesterday's Accomplishments:**
  * Designed an entire naive solution before writing a single line of code
  * Completed fruits baskets problem
  
 **Today's Goals:**
  * Don't give up
  * Continue to design solutions before coding
  * Improve illustrating logic flow through text
  example:
  
``` 
  (Showcasing an illustration of looping j numbers ( 2 - 6) of i (1))
  [ 1 2 3 4 5 6 ]
  1
  |
  2 3 4 5 6 
  |
  x x+1 x+2

  (Showcasing a sliding window of moving right and left window bounds)
  [ 1 2 3 4 5 6 ]
  
  [1] 2 3 4 5 6
  [1 2] 3 4 5 6
  [1 2 3] 4 5 6
  1 [2 3] 4 5 6
```
  * Remember to read through logic before immediately starting to debug (printing fun) (again)
  
 **Today's Accomplishments:** 
  * Completed no repeat substring
  * Designed both naive and optimal solutions before coding them (will illustrations)
  * No printing needed during debugging
 
 **Thoughts:**
  * I should really take a few days of pure hard leetcode questions before I finish all the patterns
  * I had a thought of using `set()` to accomplish this, tried to use `Set()` with dep issues then gave up on that approach.  It ended up being what I needed to do.
  * I need to start timing the design and coding sections (less than 20 minutes per problem) 
  
 **Links:**
 - [Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/no-repeat-substring.ipynb)
 
 
 ### Day 8: September 21th, 2020
  
  **Yesterday's Accomplishments:**
   * Completed no repeat substring
   * Improved pre-design of solution and illustrating before writing any code
   
  **Today's Goals:**
   * Continue to reinforce better interview habits (illustrating design, debugging mentally)
   * Complete problem
   
  **Today's Accomplishments:** 
   * Completed Longest substring with same letter replacement problem
   * My Naive solution ended up being as efficient as what a sliding window implementation would be
  
  **Thoughts:**
   * Took a realllly long time to come up with naive solution, but is efficient
   * Had lots of knowledge gap trouble with iterating over maps to get various things
   
  **Links:**
  * [Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/longest_substring_with_same_letters_replacement.ipynb)
  
 
 ### Day 9: September 22th, 2020
  
**Yesterday's Accomplishments:**
 * Completed longest substring with k replaced characters
 * naive solution was as efficient as optimal solution

**Today's Goals:**
* Continue to reinforce better interview habits (illustrating design, debugging mentally)
* Get faster

**Today's Accomplishments:** 

**Thoughts:**

**Links:**
