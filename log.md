# 100 Days Of Code - Log

### Day 0: Monday, September 7th, 2020 | :white_check_mark: | 2 hrs

**Today's Progress:** 2 hrs | First stream, planning out my #100daysofcode schedule, app planning

**Thoughts:** Not a lot of code written, but a lot of system, api, model design for `figure out dinner` app

**Link to work:** [Figure Out Dinner](https://github.com/weklund/figure-out-dinner-app)

### Day 1: Tuesday, September 8th, 2020 | :white_check_mark: | 1 hr

**Today's Progress:** 1 hr | Starting review of [Algorithms Illuminated by Tim Roughgarden](http://www.algorithmsilluminated.org/)

**Thoughts:** Rereading chapter one, created a repo so I can implement algos in the material on python notebooks.  Also thought about `figure out dinner`, maybe I should look into barcode apis as phase two and ingredient detection in a later phase

**Link to work:** [Algo review repo](https://github.com/weklund/algorithms-illuminated-notes)


### Day 2: Saturday, September 12th, 2020 | :white_check_mark: | 2 hrs

**Today's Progress:** 
 * .5 hrs  | Got local notebook environment working
 * 1.5 hrs | Implemented a working Karatsuba Multiplication solution with recursion from section 1.3 of [Algorithms Illuminated by Tim Roughgarden](http://www.algorithmsilluminated.org/)

**Thoughts:**
* Discovered great content from [Adam](https://adamlearns.com/) who just received multiple offers from FAANG companies, who streamed for 2 straight months for prep 
* Forgot that dividing multiple `int` together in Python 3 makes the answer a float 

**Links:** 
* [Algo review repo](https://github.com/weklund/algorithms-illuminated-notes)
* [Tim Karatsuba Video](https://www.youtube.com/watch?v=JCbZayFr9RE&list=PLEGCF-WLh2RLHqXx6-GZr_w7LgqKDXxN_&index=3)
* [Adam's Interview Prep](https://www.youtube.com/playlist?list=PL4Ayjzb5Bhmd1sof3Ri5yoRlUDvfnmpQ8)
* [Livestreaming your development article](https://adamlearns.com/blog/live-streaming-development)
* [Interview Prep Guide](https://docs.google.com/document/d/1eKirumpmwDWTtKCJKn2HuoQ2NavEfR41whmTyaQcio4/edit#)



### Day 3: Sunday, September 13th, 2020 | :white_check_mark: | 3.5 hrs

**Today's Progress:** 
 * 1 hr    | Started on Grokking the Coding Interview, created a [repo](https://github.com/weklund/patterns-for-coding-questions) for note taking of various patterns
 * 1 hr    | Explained the Sliding Window pattern and where it can be used
 * 1.5 hrs | Completed Max Sum of Subarray of Size K problem using Sliding Window

**Thoughts:**
 * It's tough to clean the rust of Python while streaming and reviewing forgotten concepts lol 
 * I need to get better at reading all the code when there's an issue instead of immediately printing to debug.  I'll understand it better when I run through the computations mentally.  

**Links:** 
* [Sliding Window Notebook](https://github.com/weklund/patterns-for-coding-questions/tree/master/sliding-window)

### Day 4: Monday, September 14th, 2020 | :white_check_mark: | 1.5 hrs

**Yesterday's Accomplishments:**
 * Started Grokking the Coding Interview
 * Relearned the Sliding Window pattern and took good notes
 * Solved the first problem in the series using Sliding Window
 
**Today's Goals:**
 * Remember to read through logic before immediately starting to debug (printing fun)

**Today's Accomplishments:** 
 * 1.5 hrs | Completed Smallest Subarray with a given sum problem using Sliding Window 
 * Did not have to print anything during my debugging, getting better at mentally reviewing buggy code

**Thoughts:**
 * I could have a faster recall on list comprehension
 * Had the meat of the logic correct, but I had incorrectly used the wrong loop structure.  Beat myself up pretty bad about it but I need to remember I'm actually going above and beyond what the course wants.  The real exercises aren't until the 'Problem Challenges' 

**Links:**
[Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/Smallest_subarray_with_a_given_sum.ipynb)

### Day 5: Tuesday, September 15th, 2020 | :white_check_mark: | 2 hrs

**Yesterday's Accomplishments:**
 * Completed smallest subarray with given sum question
 * Started to read through buggy code without immediately printing all the things
 
**Today's Goals:**
 * Remember to read through logic before immediately starting to debug (printing fun) (again)
 * Try to implement the optimal solution without looking

**Today's Accomplishments:** 
 * 2 hrs | Completed longest substring with k distinct characters
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


### Day 6: Thursday, September 17th, 2020 | :white_check_mark: | 2.5 hrs

**Yesterday's Accomplishments:**
 * Completed longest substring of k distinct characters
 * Used more elegant unique string selection for comparsion
 
**Today's Goals:**
 * Remember to read through logic before immediately starting to debug (printing fun) (again)
 * Try to implement the optimal solution without looking
 * Come up with the whole design for the solution before writing any code

**Today's Accomplishments:** 
 * Biggest goal met was designing the entire logic for the naive solution without writing a single line of code
 * 2 hrs  | Completed fruit basket problem
 * .5 hrs | Was able to recall the entire solution from memory from longest substring of k distinct characters

**Thoughts:**
 * Get feedback on my solution design / pseudocode ish.  Was it too iterative?
 * I gave up too quickly on the solution.  
 * NOTE: It is mentioned in the course content that this is the same problem space as the previous problem, longest substring with k distinct characters
   
   THIS IS NOT TRUE. The constraints in this problem require you to keep track of the characters to know which ones have been picked and need to be dropped off.
   
   The previous problem was only measuring contiguous unique characters. This led me down the wrong optimization path.

**Links:**
 [Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/fruits_into_baskets.ipynb)
 
 ### Day 7: Friday, September 18th, 2020 | :white_check_mark: | 2 hrs
 
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
  * 2 hrs | Completed no repeat substring
  * Designed both naive and optimal solutions before coding them (will illustrations)
  * No printing needed during debugging
 
 **Thoughts:**
  * I should really take a few days of pure hard leetcode questions before I finish all the patterns
  * I had a thought of using `set()` to accomplish this, tried to use `Set()` with dep issues then gave up on that approach.  It ended up being what I needed to do.
  * I need to start timing the design and coding sections (less than 20 minutes per problem) 
  
 **Links:**
 - [Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/no-repeat-substring.ipynb)
 
 
 ### Day 8: Monday, September 21th, 2020 | :white_check_mark: | 1.5 hrs
  
  **Yesterday's Accomplishments:**
   * Completed no repeat substring
   * Improved pre-design of solution and illustrating before writing any code
   
  **Today's Goals:**
   * Continue to reinforce better interview habits (illustrating design, debugging mentally)
   * Complete problem
   
  **Today's Accomplishments:** 
   * 1.5 hrs | Completed Longest substring with same letter replacement problem
   * My Naive solution ended up being as efficient as what a sliding window implementation would be
  
  **Thoughts:**
   * Took a realllly long time to come up with naive solution, but is efficient
   * Had lots of knowledge gap trouble with iterating over maps to get various things
   
  **Links:**
  * [Notebook](https://github.com/weklund/patterns-for-coding-questions/blob/master/sliding-window/longest_substring_with_same_letters_replacement.ipynb)
  
 
 ### Day 9: Tuesday, September 22th, 2020 | :red_circle: | .5 hrs
  
**Yesterday's Accomplishments:**
 * Completed longest substring with k replaced characters
 * naive solution was as efficient as optimal solution

**Today's Goals:**
* Continue to reinforce better interview habits (illustrating design, debugging mentally)
* Get faster

**Today's Accomplishments:** 

**Thoughts:**

**Links:**

### Days 10 - 13: September 23th - September 26th 2020 | :red_circle:

Unfortunately a combination of meetings and distress of lead up to and after the announcement from the Kentucky AG about Breonna Taylor :(

### Day 14: Sunday, September 27th 2020 | :red_circle: | 1 hr

**Today's Accomplishments:**  
* 1 hr | Wrote up Check Mirrored Trees Problem

### Day 15: Monday, September 28th 2020 | :white_check_mark: | 3.5 hrs

**Today's Accomplishments:** 

* .5 hrs  | Published my first DEV.to article 
* 1.5 hrs | Completed a LeetCode mock interview where I answered an easy and a medium question under a timelimit.
* 1.5 hrs | Highlighted all my previous naive and optimal solutions from streams before the broadcasts disappear

**Links:**

* [DEV.to article](https://dev.to/weklund/first-dev-post-yet-another-post-about-interviewing-for-faang-100daysofcode-3i1j)
* [Leetcode mock interview question](https://leetcode.com/problems/prison-cells-after-n-days/)
 
### Day 16: Tuesday, September 29th, 2020 | :white_check_mark: | 2 hrs
  
**Yesterday's Accomplishments:**
 * Published my first DEV article
 * Completed a Leetcode mock interview where I answered 'Two Sum' and 'Prison Cells on Nth Day'

**Today's Goals:**
* Debug Check Mirrored Trees code
* Understand optimal solution for 'Prison Cells After N Days'
* Continue to reinforce better interview habits (illustrating design, debugging mentally)

**Today's Accomplishments:** 
* 1 hr | Debugged Check Mirror Trees (test case was wrong :( )
* 1 hr | See optimal solution for prison cells but do not fully understand

**Thoughts:**
* Do not want to call prison cells done until I go through the bitwise XOR section on Grokking
**Links:**

### Day 17: Wednesday, September 30th, 2020 | :red_circle: | 1 hr
  
**Yesterday's Accomplishments:**
 * Debugged is mirror tree code
 * Investigated prison cells problem

**Today's Goals:**
* Mock interview

**Today's Accomplishments:** 
* 1 hr | Did not pass mock interview but learned a great optimal solution using stacks
* Have in person mock scheduled for tomorrow

**Links:**
* [Mock interview question](https://leetcode.com/problems/basic-calculator/)

### Day 18: Thursday, October 1st, 2020 | :white_check_mark: | 2 hrs
  
**Yesterday's Accomplishments:**
 * Mock Interview given Basic Calculator problem
 
**Today's Goals:**
* EPI 4.8
* 1:1 mock interview (give either reverse string or basic calculator)
* Start writing "Why I suck at Coding Interview" (Refer to start of stream monologue)

**Today's Accomplishments:** 
* 2 hrs | Started on 5.2, designed solution in pseudocode 

**Thoughts**
* Forgot that `//` is cool.  Better than using `floor()` for floor division

**Links:**
* [EPI 4.8 - Reverse String (Digits)](https://leetcode.com/problems/reverse-string/)

### Day 19: Friday, October 2nd, 2020 | :red_circle: | 1 hr
  
**Yesterday's Accomplishments:**
* Started on 5.2 of EPI
 
**Today's Accomplishments:** 
* 1 hr | Watched some 'Welcome to the coding interview: you suck' videos

### Day 20: Saturday, October 3rd, 2020 | :red_circle: | .5 hrs
  
**Yesterday's Accomplishments:**
* Watched some videos
 
**Today's Accomplishments:** 
* .5 hrs | Created a Python notebook to refresh syntax and standard library functions

### Day 21: Sunday, October 4th, 2020 | :red_circle: | 1 hr
  
**Yesterday's Accomplishments:**
* Created a Python notebook to refresh syntax and standard library functions
 
**Today's Accomplishments:** 
* 1 hr | Took notes from AlgoExpert Data Structures video

### Day 22: Monday, October 5th, 2020 | :red_circle: | .5 hrs
  
**Yesterday's Accomplishments:**
* Took notes from AlgoExpert Data Structures video
 
**Today's Accomplishments:** 
* .5 hrs | Did a Algos prep quiz

### Day 23: Tuesday, October 6th, 2020 | :white_check_mark: | 4 hrs 
  
**Yesterday's Accomplishments:**
* Took a algo quiz

**Today's Goals:**
- [x] Catch up #100DaysOfCode log
- 1.5 hrs |  [x] Take notes from watching AlgoExpert videos:
    - [x] Memory
    - [x] Big O
    - [x] Log
    - [ ] Arrays
    - [ ] Linked Lists
- [ ] Leetcode October Challenge question
- [ ] Twitch Chatbot (!today, !question) and timer countdown 
 
**Today's Accomplishments:** 
* 1.5 hrs | Completed 5.2 Plus one
* 1.5 hrs | Refreshed on AlgoExpert's Memory, Big 0, and Log lessons

**Thoughts**
* didn't know that `%=` was a thing

**Links:**
- [PlusOne](https://github.com/weklund/patterns-for-coding-questions/blob/master/EPIs/5-2_increment-precision-integer-OR-plus-one.ipynb)
- [Sudoku](https://github.com/weklund/patterns-for-coding-questions/blob/master/EPIs/5-17_valid-sudoku.ipynb))


### Day 24: Wednesday, October 7th, 2020 | :white_check_mark: | 2.5 hrs
  
**Yesterday's Accomplishments:**
* Completed EPI 5.2 - Plus One
* Take notes from AlgoExpert videos
* Solved problems from Python refresher on Hackerrank

**Today's Accomplishments:**
- 1 hr   | [x] Take notes from watching AlgoExpert videos:
    - [x] Arrays
    - [x] Linked Lists
- 1 hr   | [x] Mock Interview
- .5 hrs |[x] Start 'Why I suck at Coding Interviews'
- [ ] Leetcode October Challenge question
- [ ] Twitch Chatbot (!today, !question) and timer countdown 

**Thoughts**
* Each mock interview is great since it either reinforces what I'm already doing to prep or tweaks it to add what I'm missing
* Stop thinking I need to rush the material.  Becoming a master of the topics will come, just keep putting in the hours every day


### Day 25: Thursday, October 8th, 2020 | :white_check_mark: | 3.5 hrs 
  
**Yesterday's Accomplishments:**
* Mock Interview
* Finished refreshing Arrays and Linked Links from AlgoExpert
* Solved problems from Python refresher on Hackerrank

**Today's Accomplishments:**
- 1 hr    | [x] Take notes from watching AlgoExpert videos:
    - [x] Hash Tables
    - [x] Stacks and Queues
- 1.5 hrs | [x] Helped a friend conduct a Mock Interview
- 1 hr    | [x] 2 Problems on Hackerrank Python refresher

**Thoughts**
* I think I'm going to make flash cards on the time complexities of each operation for every data structure (set, insertion, deletion, search etc etc)


### Day 26: Friday, October 9th, 2020 | :white_check_mark: | 4 hrs
  
**Yesterday's Accomplishments:**
* Notes for Hash tables, Stacks and queues
* Helped a friend conduct a Mock Interview
* Solved problems from Python refresher on Hackerrank

**Today's Accomplishments:**
- 2.5 hrs | [x] Take notes from watching AlgoExpert videos:
    - [x] Strings
    - [x] Graphs
    - [x] Trees
- .5 hrs  | Made Flash Cards of various operations on different data structures
- 1.5 hrs | Deep Dive on using Two Pointers for solving the array sum problem

**Thoughts**
* I think I'm going to start my daily schedule with deep dive with a problem or two in morning, and study core concepts / quizzes in the afternoon


### Day 27: Saturday, October 10th, 2020 | :white_check_mark: | 3.5 hrs
  
**Yesterday's Accomplishments:**
* Finished notes for Strings, Graphs, and Trees
* Made Flash Cards
* Deep Dive on Two Pointers

**Today's Accomplishments:**
- 2 hrs   | Deep Dive on Validate Subsequence problem
- 1.5 hrs | 3/4 done on Deep Dive for Find Closest Value in BST


### Day 28: Sunday, October 11th, 2020 | :yellow_circle: | 0
  
(Took the day off)

### Day 29: Monday, October 12th, 2020 | :red_circle: | 0
  
(Took the day off)


### Day 30: Tuesday, October 13th, 2020 | :white_check_mark: | 6 hrs
  

**Today's Accomplishments:**
- 2 hrs | Completed MIT 6.006 Lecture 1 on Algorithmic Thinking and Peak Finding
- 4 hrs | Started on Study Guide

**Thoughts**
- My plan for study guide will be to have each common DS and Algo listed with:
    - Brief Overview
    - Visualize or picture of the DS/Algo
    - Explain why it exists (Why would you choose this one over others)
    - Pros/Cons list
    - What is this optimized for?
    - Big O for various operations (retrival, access, insertion, deletion, etc) 
    - Code Implentation 
    
    
 
### Day 31: Wednesday, October 14th, 2020 | :white_check_mark: | 4 hrs
  

**Today's Accomplishments:**
- 3.5 hrs | Completed MIT 6.006 R1 and assignment setup
- .5 hrs  | Reviewed current notes

**Links**

https://github.com/weklund/MIT_6.006_Intro-to-Algorithms

### Day 32: Thursday, October 15th, 2020 | :white_check_mark: | 6.5 hrs
  

**Today's Accomplishments:**
- 1.5 hrs | Deep Dive into E4 - Branch Sums Problem
- 2 hrs   | Completed MIT 6.006 L2 - Models of Computation, Document Distance
- 2 hrs   | Completed #leetcode Path Sum problem
- .5 hrs  | Worked more on Study Guide

**Links**

https://leetcode.com/problems/path-sum/
    
### Day 33: Friday, October 16th, 2020 | :white_check_mark: | 4.5 hrs
  

**Today's Accomplishments:**
- 1.5 hrs | Deep Dive into E5 - Node Depths Problem
- 1.5 hrs | Watched/took notes on MIT 6.006 R2 - Models of Computation, Document Distance
- .5 hrs | Learned about using literative approach with stacks to solve tree problem
- 1 hrs | Worked more on Study Guide

**Links**

https://www.youtube.com/watch?v=QFcyt8fgQMU&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=26
    

### Day 34: Saturday, October 17th, 2020 | :white_check_mark: | 4 hrs
  
**Today's Accomplishments:**
- 2.5 hrs | Worked more on filling out Study Guide
- 1.5 hrs | Watched/took notes on MIT 6.006 L3 - Insertion Sort, Merge Sort

**Links**

https://www.youtube.com/watch?v=Kg4bqzAqRBM&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb&index=3&t=1s


### Day 35: Sunday, October 18th, 2020 | :red_circle: | 1.5 hrs
  
**Today's Accomplishments:**
- 1.5 hrs | Read a few chapters from the book Grokking Algorithms

**Links**

https://www.amazon.com/Grokking-Algorithms-illustrated-programmers-curious/dp/1617292230


### Day 36: Monday, October 19th, 2020 | :white_check_mark: | 3.5 hrs
  
**Today's Accomplishments:**
- 1 hrs | Had a mock interview through interviewing.io
- 1 hrs | Coded up some recursion problems from the book Grokking Algorithms
- .5 hrs | Deep dive into E6 - Depth first Search
- .5 hrs | Uploaded notes from MIT 6.006 L2/R2
- .5 hrs | Prepped for FAANG behavioral interview questions


### Day 37: Tuesday, October 20th, 2020 | :yellow_circle: | 1 hrs
  
**Today's Accomplishments:**
- Had my first FAANG technical interview today!


### Day 38: Wednesday, October 21th, 2020 | :yellow_circle: | 0 hrs
  
- Off today

### Day 39: Thursday, October 22nd, 2020 | :white_check_mark: | 3 hrs
  
- 1 hrs | Deep dive on E7 - Nth Fibonacci
- 1 hrs | Finish MIT 6.006 R3
- 1 hrs | Read 2 more chapters on Grokking Algorithms

### Day 40: Friday, October 23th, 2020 | :red_circle: | 2 hrs
  
- 1.5 hrs | Deep dive on E8 - Product Sum
- .5 hrs | Read breath first search on Grokking Algorithms

### Day 41: Saturday, October 24th, 2020 | :red_circle: | 1 hrs
  
- .5 hrs | Read more Grokking Algorithms
- .5 hrs | Read up on behavioral interview prep

### Day 42: Sunday, October 25th, 2020 | :red_circle: | 0
  
- off day

### Day 43: Monday, October 26th, 2020 | :red_circle: | 2.5 hrs
  
- 1 hr   | Read Grokking Algorithms Chapter
- 1 hr   | Mock Behavioral Prep
- .5 hrs | Review prep for 2nd FAANG technical screen

### Day 44: Tuesday, October 27th, 2020 | :red_circle: | 2 hrs
  
- 1 hr   | Reviewed Graph and Tree structures
- 1 hr   | Read Grokking Algorithms chapter on Dynamic Programming

### Day 45: Wednesday, October 28th, 2020 | :red_circle: | 2 hrs
  
- 2 hrs   | Reviewed Systems Design interviews

### Day 46: Thursday, October 29th, 2020 | :red_circle: | 2 hrs
  
- 1 hr   | Reviewed Systems Design format
- 1 hr   | Systems Design Mock Interview

### Day 47: Friday, October 30th, 2020 | :red_circle: | 1.5 hrs
  
- 1 hr   | Complete E9 - Binary Search
- .5 hrs | Reviewed feedback from Systems Design interview

- Scheduled FAANG-2 technical screen
- Scheduled FAANG-1 on-site final interviews

### Day 48: Saturday, October 31th, 2020 | :white_check_mark: | 4.5 hrs
  
- 1.5 hrs | Plan out study/content schedule until FAANG-2 technical screen
- 1 hr    | Deep dive on E10 - Find 3 Largest Numbers
- 1 hr    | Deep dive on E11 - Bubble Sort
- 1 hr    | Deep dive on E12 - Insertion Sort

### Day 49: Sunday, November 1st, 2020 | :white_check_mark: | 4.5 hrs
  
- 1.5 hrs | Watch MIT 6.006 L4 - Heaps and Heap Sort
- 1 hr    | Complete E13 - Selection Sort
- 1 hr    | Review Notes / Study Guide
- 1 hr    | Mock Coding Interview

### Day 50: Monday, November 2nd, 2020 | :white_check_mark: | 4.5 hrs
  
- 1.5 hrs | Watch FAANG Prep Coding Approach
- .5 hrs  | Complete E14 - Check Palindrome
- 1.5 hrs | STAR Stories
- 1 hr    | Mock Behavior Interview

### Day 51: Tuesday, November 3rd, 2020 | :white_check_mark: | 6.5 hrs
  
- 3 hrs | Watch more FAANG Coding Approach
- 2 hrs | Study Interview Tips
- 1 hr  | Start Sorting Guide
-.5 hrs | Watch / take notes on good interviews

### Day 52: Wednesday, November 4th, 2020 | :white_check_mark: | 5.5 hrs
  
- 1 hrs | Finish Gayle's Coding Interview approach
- 2.5 hrs | Deep Dive into DFS
- 1 hr  | Review Problem Solving process
- 1 hr  | Mock Coding Interview

### Day 53: Thursday, November 5th, 2020 | :white_check_mark: | 4.5 hrs
  
- 4.5 hrs | Worked on Grokking Coding Interviews - Deep dive on DFS problems


### Day 54: Friday, November 6th, 2020 | :white_check_mark: | 3 hrs
  
- 1.5 hrs | Review Graph data structure and various algos for it
- .5 hrs  | Review problem solving approach
- 1 hr    | FAANG Phone Interview!!

### Day 55: Saturday, November 7th, 2020 | :yellow_circle: | 0
  
- Took day off

### Day 56: Sunday, November 8th, 2020 | :yellow_circle: | 0
  
- Took day off

### Day 57: Monday, November 9th, 2020 | :red_circle: | 1.5 hrs
  
- .5 hrs | Watched video on bitwise XOR
- 1 hr   | Worked on algorithms

### Day 58: Tuesday, November 10th, 2020 | :red_circle: | 1.5 hrs
  
- 1 hr   | Grokking DFS
- .5 hrs | Review E4-E9

### Day 59: Wednesday, November 11th, 2020 | :white_check_mark: | 5 hrs
  
- 1 hr   | Deep dive on E15 Cipher Encryptor
- 1.5 hrs | Deep dive on LC FAANG #3
- 1 hr    | Deep dive on LC FAANG #1192
- 1 hr    | Call with FAANG for on-site prep
- .5 hrs  | Call with FAANG-3 recruiter

### Day 60: Thursday, November 12th, 2020 | :white_check_mark: | 7.5 hrs
  
- 4 hrs   | Craft behavioral stories using STAR
- 2 hrs   | Review Systems Design guide
- 1.5 hrs | Review prep / gaps and plan schedule til on-sites

### Day 61: Friday, November 13th, 2020 | :white_check_mark: | 7.5 hrs
  
- 6 hrs   | Solving Sliding window problems
- 1.5 hrs | Mock coding interview using @interviewingio

### Day 62: Saturday, November 14th, 2020 | :yellow_circle: | 0
  
- Took the day off

### Day 63: Sunday, November 15th, 2020 | :red_circle: | 1 hr
  
- 1 hr | Review LPs

### Day 64: Monday, November 16th, 2020 |  :yellow_circle: | 1.5 hrs
  
- 1 hr   | Behavior mock interview
- .5 hrs | FAANG-3 call for on-sites

### Day 65: Tuesday, November 17th, 2020 | :yellow_circle: | 2 hrs
  
- 2 hrs   | System Design Mock interview

### Day 66: Wednesday, November 18th, 2020 | :yellow_circle: | 1 hr
  
- 1 hr | Behavior mock interview

### Day 67: Thursday, November 19th, 2020 | :white_check_mark: | 6 hours

- 6 hrs | FAANG-1 final interviews
