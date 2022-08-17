# CMPSC 130A: Data Structures and Algorithms I (Summer 2022)

Instructor: Md Shafiuzzaman (mdshafiuzzaman@ucsb.edu), Please call me Shafi. 

Lecture Time: 2 pm-2:50 pm, TWR, 387 1011 

Office hour: 4:00pm-5:00pm, Wed, Zoom: https://ucsb.zoom.us/j/4512414633

Piazza: https://piazza.com/ucsb/summer2022/cmpsc130a


## Quick References

- Teaching Assistant: Boxun Xu (boxunxu@ucsb.edu), Office hour 9:00-10:00 AM, Mon
- Discussion Sections: F 10:00-10:50, 387 1011   
- All course-related communication will be through piazza.
- Submit your homework through gradescope (you will be added when class starts).  
- Programming assignments will be on kattis. Please	remember to	*both*	make	an	account	on	UCSB.kattis	AND	register	for	the	course	[information	to	be	posted	on	Piazza].	Use	*exactly*	the	same	 name	on	Kattis	as	on	E-grades/Gold.
- Reading assignments will be in Algorithm Design and Applications from zybooks. Manage a subscription for this book. Subscription details:
    1. Sign in or create an account at learn.zybooks.com
    2. Enter zyBook code: UCSBCMPSC130AShafiuzzamanSummer2022
    3. Subscribe (A subscription is $58. Students may begin subscribing on Jun 08, 2022 and the cutoff to subscribe is Aug 27, 2022. Subscriptions will last until Sep 16, 2022)
    4. Help center: https://zybooks.zendesk.com/hc/en-us/categories/360004050694-Students 
## Course description
The study of data structures and their applications. Correctness proofs and techniques for the design of correct programs. Graph traversal techniques and their applications. Searching. Hashing and balanced trees. Analysis of sorting algorithms.

## Learning Objectives:
### 1. Compare the structures, usages, strengths, and weaknesses of different data structures
Students will compare different data structures such as stack, queue, hashtables, trees, graphs,  and heaps, and their performances in different scenarios. There will be multiple Homework focusing on this objective.

### 2. Choose the appropriate data structures and algorithms to solve a given problem
Students will demonstrate their problem-solving skills by formulating a problem using fundamental data structures and algorithms. They may need to modify the known data structures and the algorithms or design new ones to solve a given problem programmatically. Programming assignments will be prepared to achieve this objective. 

### 3. Develop correct solutions to a problem and reason about the correctness
Students will infer the solution from the problem statement, use the correct combination of data structures and algorithms, and most importantly verify the correctness of their solutions with logical explanations. Homeworks, midterm and final will be designed to assess this objective. 

### 4. Evaluate the efficiency of the algorithms 
Students will extract the complexity of the algorithms and deduce them into best-case, average-case, and worst-case running times. Thus they will be able to infer the complexity of their own algorithms. Homeworks, midterm and final will be designed to assess this objective. 

### 5. Identify the loopholes in the implementation of an algorithm and optimize those to develop an efficient one
Students will make their programming assignments accepted by the auto graders. Programming auto graders may not accept a solution until it achieves a certain optimization level. Therefore, students will identify the complex part of their implementations and optimize their source codes to ensure better performance.

## Textbook
- Algorithm Design and Applications from  zybooks

## How to succeed in this course 
It is important to understand the implementation scope of the algorithms rather than simply grabbing those.  To this end, your success will largely depend on you completing homeworks on time. Because homework problems will also guide you for midterm and final. We have a significant amount of availability to help you work through problems, so please take advantage of our office hours.  Working through problems together is a lot of fun, so you should find study partners to work with this summer as well! Attending lectures and discussion sections, however, will be important for you to acquire basic knowledge to succeed with assignments.  



## Course Schedule


| Date  | Topic                                         | Out | Due |
|-------|-----------------------------------------------|-----|-----|
**Week-1**|**Introduction and Algorithm Efficiency**|-----|-----|
| 6/21  | Introduction                                  | RA1      |     |
| 6/22  | Growth of functions and complexity, O-notation                          |     |     |
| 6/23  | Graph introduction & representation|     |   RA1   |
**Week-2**|**Graphs**|-----|-----|
| 6/28 |  Breadth-first search         | RA2, HW1   |  |
| 6/29 |  Depth-first search                           |  |     |  
| 6/30 |  Directed graphs, Topological sort                           | |RA2   |
**Week-3**|**Hashing I**|-----|-----|
| 7/5 | Hashing introduction, Pegion hole principle, Birthday paradox               |  RA3    |    |
| 7/6 | Handling collisions: Balls in bins formula, separate chaining                        |    |  |
| 7/7 | Handling collisions: Separate chaining in random setting, probing                                   |   |  RA3, HW1     |
**Week-4**|**Hashing II**|-----|-----|
| 7/12 | Hash function constructions, Merkle-Damgard Hash Function                       |  RA4, PA1   |  |
| 7/13  | Universal hashing            |  |     |
| 7/14  | Perfect hashing                      |  |    RA4    | 
**Week-5**|**Priority Queues and Heaps**|-----|-----|
| 7/19  | Heaps, Time Complexity of building a heap, Applications of Heaps                                | RA5     |   |
| 7/20 |  Priority Queues, Heapsort                                      |      | |
| 7/21 |  Leftist Heap    |   | RA5, PA1    |
**Week-6**|**Shortest Paths**|-----|-----|
| 7/26 | MIDTERM                                        | PA2, RA6    |     |
| 7/27 | Weighted graphs, Algorithm: Dijkstra's shortest path |     ||
| 7/28 | The Bellman-Ford algorithm                            | | RA6   |
**Week-7**|**MST and Union Find Data Structure**|-----|-----|
| 8/2  |  MST,  Kruskal algorithm, Union-find and list-based implementation                            |  RA7    |      |
| 8/4  | Union By Rank and Path Compression, Kruskal (Cont.)                   |    |RA7, PA2|
**Week-8**|**MST and Amortized Analysis**|-----|-----|
| 8/9  | Prim's algorithm                          |  RA8, HW2    |    |
| 8/10  | Amortized analysis                          |     |  |
| 8/11  | Amortized analysis (Cont.)                       |  |  RA8    |
**Week-9**|**BST**|-----|-----|
| 8/16  | Search, Insert, Delete, Self-balancing BST                      | RA9    |   |
| 8/17 | AVL insertions, AVL removals                       |     |     |
| 8/18 | Balanced BST                                  |     |  RA9, HW2  |
**Week-10**|**AVL Tress**|-----|-----|
| 8/23 | Red Black Tree                  |   RA10    |  |
| 8/24 | Problem Solving                               |     |  RA10     |
| 8/25 | Final                                          |     |  |


## Grade Composition

1. zyBooks Reading Assignments (RA): 15% 

2. Homeworks (HW): 20%
    1. HW with best score, 12% 
    2. Others, 8%

3. Programming Assignments (PA): 25%
    - PA with best score 15% and others 10%
    - Randomely picked 50% of the students will be asked to come for a code review session. 
    - Each PA will be comprised of multiple problems (may have bonus and optional problems)  
          
3. Midterm Exam: 20%
4. Final Exam: 20%

Grade ranges (using mathematical interval notation): A+: [97,100]; A: [93,97); A-: [90,93); B+: [87,90); B: [83,87); B-: [80,83); C+: [77,80); C: [73,77); C-: [70,77); D+: [67,70); D: [63,67); D-: [60,63); F: [0,60).  

We will round final raw scores to the nearest whole number to compute your final grade.  Thus, if you score an 89.7 in the class, you’ll get an A-.  If you score an 82.48, you’ll get a B-.  Notice that this will never adversely affect your grade.  For example, if you score a 77.3, your raw score will be rounded to 77, but both 77.3 and 77 are a C+ so your final grade is unaffected. 


## Class Policy
- After each reading assignment, submit the online quizzes included in zyBooks within the due date. The due dates are added in the zybooks. Reding assignments will help to gather the basics of each of the topics. Please complete it on time, we cannot provide you any extesion for this since it may affect your learning curve. 
 
- For homework assignments, please submit your solution in Gradescope.  No late submissions are accepted (Due at 11:00 PM) since we need to provide you feedback before midterm and final.
 
- You may discuss homework problems with your classmates, but please write down your own solution and acknowledge your collaborators. 

- For homeworks and programming assignments, you must understand and be able to explain every single line that you hand in. Not being able to explain handed in work counts as cheating. You may be asked for code review session for programming assignments.
 
- For homework problems and programming assignments you may not consult anyone other than fellow students, course instructors, or TA's regarding anything pertaining to particular homework problems. You are allowed to ask about general topics (greedy algorithms, solving recurrences) but nothing related to a particular problem (how do I solve *this* recurrence, how do I analyze *this* algorithm, etc). Of course, there are grey zones. Err on the side of caution.
 
- The policy above also applies to searching the internet and asking questions on forums. 
 
- Do not post solutions to homework problems or programming assignments online.

## Academic Integrity

All students are expected to understand and comply with university policies regarding academic integrity.  Please understand that we take academic integrity seriously.  Cheating, plagiarism, and other acts of academic dishonesty completely defeat the purpose of academia.  You are expected to present your own work when submitting assignments for grading and you are expected to not misuse academic sources.  You can view the university’s policy on student conduct at https://www.sa.ucsb.edu/regulations/student-conduct-code/student-conduct-code.



You may:

- Discuss broad ideas about programming assignments in groups, without being at a computer (with code-writing and debugging done individually, later).
- Work with your peers on homework assignments, provided you write up your final full solution set on your own.
- Ask the instructor or TAs questions and use their explanations to accomplish your assignments.
- Check out course reserves or other textbooks for free at the library.


You may not:
- Collaborate with anyone in any way on reading assignments, midterm, and final.  
- Discuss programming assignments with someone who has already completed the problem, or looking at their completed solution.
- Leave your solutions or code (for example in an online repository) visible to others, leading others to look at your solution.
- Post course materials to Chegg, Stackexchange, or other tutoring sites.

What are the consequences of committing academic dishonesty of any kind?

- For your first offense, you will receive a 0 on assignments which are completed by violating the student conduct code.  Further sanctions are decided by the Office of Student Conduct. 


## Accommodations for Students with Disabilities
Students with disabilities may request academic accommodations for exams online through the ​UCSB Disabled Students Program​. Please make requests for exam accommodations through the online system as early in the class as possible to ensure proper arrangement. https://dsp.sa.ucsb.edu/services/ 

Please note that exam accommodations will only be granted after the DSP office receives your requests, processes it, approves it, and informs the teaching staff in writing. 

## Syllabus Changes

As we move through the course, some changes may be necessary to ensure a smoothly run class.  I reserve the right to alter the syllabus in a reasonable fashion, provided I give everyone at least 24 hours advance notice.   

## Acknowledgements

This course is higly motivated by the spring'22 course of Prof. Daniel Lokshtanov (https://sites.cs.ucsb.edu/~daniello/)
