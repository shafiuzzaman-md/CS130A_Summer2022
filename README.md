# CS130A Data Structures and Algorithms (Summer 2022)

Instructor : Md Shafiuzzaman (mdshafiuzzaman@ucsb.edu), Please call me Shafi. 

Lecture Time: 2pm-2:50pm, TWR, 387 1011 

Office hour: 4:00pm-5:00pm, Fri, Zoom: https://ucsb.zoom.us/j/4512414633

Piazza: https://piazza.com/configure-classes/summer2022/cs130a


## Quick References

- Teaching Assistant: TBA
- All course-related communication will be through piazza.
- Submit your homework through gradescope (you will be added when class starts).  
- Programming assignments will be on kattis. Create an account in kattis and your name on kattis should match with your name provided in Gold. 
- Reading assignments will be in Data Structure Essentials with C++ and Algorithm Design and Applications from zybooks. Manage a merged subscription of these two books. 

## Course description
The study of data structures and their applications. Correctness proofs and techniques for the design of correct programs. Graph traversal techniques and their applications. Searching. Hashing and balanced trees. Analysis of sorting algorithms.

## Learning Objectives
### 1. Compare the structures, usages, strengths, and weaknesses of different data structures
Students will compare different data structures such as stack, queue, hashtables, trees, graphs,  and heaps, and their performances in different scenarios. There will be multiple Homework focusing on this objective.

### 2. Choose the appropriate data structures and algorithms to solve a given problem
Students will demonstrate their problem-solving skills by formulating a problem using fundamental data structures and algorithms. They may need to modify the known data structures and the algorithms or design new ones to solve a given problem programmatically. Programming assignments will be prepared to achieve this objective. 

### 3. Develop correct solutions to a problem and reason about the correctness
Students will infer the solution from the problem statement, use the correct combination of data structures and algorithms, and most importantly verify the correctness of their solutions with logical explanations. Midterms and finals will be designed to assess this objective. 

### 4. Evaluate the efficiency of the algorithms 
Students will extract the complexity of the algorithms and deduce them into best-case, average-case, and worst-case running times. Thus they will be able to infer the complexity of their own algorithms. Midterms and finals will be designed to assess this objective. 

### 5. Identify the loopholes in the implementation of an algorithm and optimize those to develop an efficient one
Students will make their programming assignments accepted by the auto graders. Programming auto graders may not accept a solution until it achieves a certain optimization level. Therefore, students will identify the complex part of their implementations and optimize their source codes to ensure better performance.

## Textbook
- Data Structure Essentials with C++ from zybooks
- Algorithm Design and Applications from  zybooks
We will be using a merge of these two textbooks from zybooks for reading assignments. 

## Class Policy
- After each reading assignment, submit the online quizzes included in zyBooks within the due date. The due dates are added in the zybooks.
 
- For homework and programming assignments, please submit your solution in Gradescope.  No late submissions are accepted (Due at 11:00 PM). With very few exceptions [e.g. documented medical emergency], no personal extensions/exceptions will be given.
 
- You may discuss homework with your classmates, but please write down your own solution and acknowledge your collaborators. You must understand and be able to explain every single line that you hand in. Not being able to explain handed in work counts as cheating. 
 
- For homework problems and programming assignments you may not consult anyone other than fellow students, course instructors, or TA's regarding anything pertaining to particular homework problems. You are allowed to ask about general topics (greedy algorithms, solving recurrences) but nothing related to a particular problem (how do I solve *this* recurrence, how do I analyze *this* algorithm, etc). Of course, there are grey zones. Err on the side of caution.
 
- The policy above also applies to searching the internet and asking questions on forums. 
 
- Do not post solutions to homework problems online. You may post your programs for programming assignments online, but do not post any explanations/analyses.

## Grade Composition
15% zyBooks Reading Assignments
20% Homeworks (HW) (2 Homeworks counting 10% each)
20% Programming Assignments* (PA) (2 Assignments counting 10% each)
15% Midterm Exam
30% Final Exam

* Programming assignments will be comprised of multiple problems and students will be graded with the problem he receives the highest score. 

## Course Schedule


| Date  | Topic                                         | Slides | Read | Out | Due |
|-------|-----------------------------------------------|--------|------|-----|-----|
| 6/21  | Introduction                                  |  [lec1](lectures/lecture1.pdf)      |      |     |     |
| 6/22  | Algorithm efficiency, Constant time operations        |  [lec2](lectures/lecture2.pdf)      |  R1    |  [HW1](hw1/HW1.md)   |     |
| 6/23  | Growth of functions and complexity, O-notation             |  [lec3](lectures/lecture3.pdf)      |  R2    |     |     |
| 6/28  | Graph Introduction & Representation                           |  [lec4](lectures/lecture4.pdf)     |      |     | R1    |
| 6/29 | Breadth-first search                          |  [lec5](lectures/lecture5.pdf)      |      |   [HW2](hw2/HW2.md)  |   HW1  
| 6/30 | Depth-first search                            |  [lec6](lectures/lecture6.pdf)      |  R3    |     |  R2   |
| 7/5 | Directed graphs, Topological sort                           |  [lec7](lectures/lecture7.pdf)      |      |     |  HW2   |
| 7/6 | Lists, Queues              | [lec8](lectures/lecture8.pdf)        |      |    |  R3   |
| 7/7 | Hash tables, Hash functions                             |  [lec9](lectures/lecture9.pdf)       |      |     |     |
| 7/12 | Analysis of Hashing                      |  [lec10]       |  R4    |     |  Proposal (2 pages)   |
| 7/13  | Universal Hashing, Perfect Hashing  | [lec11](lectures/lecture10.pdf)        |      |     |     |
| 7/19  | Heaps, Heaps using arrays |    [lec12](lectures/lecture11.pdf)    |      |     |     |
| 7/20 | Heapsort |   [lec](https://tinyurl.com/yu6v655m)     |      |     |     |
| 7/21 | Priority queue                   |     [lec](https://tinyurl.com/yseccv6x)    |       |     |   R4 |
| 7/26 | MIDTERM               |   [lec13](lectures/lecture13.pdf)      |      |  [HW3](hw3/HW3.md)   |     |
| 7/27 | Weighted Graphs, Algorithm: Dijkstra's shortest path       |         |      |     |    |
| 7/28 | Kruskal algorithm  |         |      |     |     |
| 8/2  | Prim's algorithm                                 |        |      |     |    |
| 8/3  | Union Find Data Structure                                  |        |      |     |  Final Report (8 pages), HW3  |
| 8/4  | Union Find Data Structure                                 |        |      |     |  Final Report (8 pages), HW3  |
| 8/9  | Amortized Analysis I                                |        |      |     |  Final Report (8 pages), HW3  |
| 8/10  | Amortized Analysis II                                  |        |      |     |  Final Report (8 pages), HW3  |
| 8/11  | Binary search trees I                                  |        |      |     |  Final Report (8 pages), HW3  |
| 8/16  | Binary search trees II                                 |        |      |     |  Final Report (8 pages), HW3  |
| 8/17 | Balanced Search Trees                                 |        |      |     |  Final Report (8 pages), HW3  |
| 8/18 | AVL rotations                                 |        |      |     |  Final Report (8 pages), HW3  |
| 8/23 | AVL insertions, AVL removals                                 |        |      |     |  Final Report (8 pages), HW3  |
| 8/24 | Problem Solving                                 |        |      |     |  Final Report (8 pages), HW3  |
| 8/25 | Final                                |        |      |     |  Final Report (8 pages), HW3  |



# Grading (No curving)

1. Programming assignments: 40%
    1. 4 programming assignments, 10% each

2. Paper reviews: 20%
    1. 4 papers, 5% each
        
3. Final project: 40%
    1. Team formed by deadline: 5%
    2. 1-page project proposal: 10%
    3. Project presentation (Poster): 10%
    4. Executable code: 5%
    5. Final report: 10%

| Letter | Percentage |
|--------|------------|
| A+     | 95–100%    |
| A      | 90–94%     |
| A-     | 85–89%     |
| B+     | 80–84%     |
| B      | 75–79%     |
| B-     | 70–74%     |
| C+     | 65–69%     |
| C      | 60–64%     |
| F      | <60%       |

### Submission
1. Please submit your homework to gradescope: https://www.gradescope.com
2. All paper reviews should be in PDF.

# Homework

1. [Homework1](hw1/HW1.md)
2. [Homework2](hw2/HW2.md)
3. [Homework3](hw3/HW3.md)

# Reading assignments
1. A Lightweight Symbolic Virtual Machine for Solver-Aided Host Languages. Emina Torlak and Rastislav Bodik. PLDI'14.
2. Program synthesis using conflict-driven learning. Yu Feng, Ruben Martins, Osbert Bastani, and Isil Dillig.  PLDI'18. **Distinguished Paper Award** 
3. Scaling symbolic evaluation for automated verification of systems code with Serval. Luke Nelson, James Bornholt, Ronghui Gu, Andrew Baumann, Emina Torlak, and Xi Wang. SOSP'2019. **Best Paper Award**
4. C. A. R. Hoare. An axiomatic basis for computer programming. Communications of the ACM, vol. 12, no. 10. 1969. ACM DL. **Turing Award**


Tips for writing paper [reviews](REVIEW.md).

Tips for writing a project [proposal](PROPOSAL.md).

# References

- Rondon, Patrick M., Ming Kawaguci, and Ranjit Jhala. "Liquid types." PLDI'2008.

- Ali Sinan Köksal, Yewen Pu, Saurabh Srivastava, Rastislav Bodík, Jasmin Fisher, Nir Piterman. Synthesis of biological models from mutation experiments. Principles of Programming Languages (POPL). 2013. ACM DL

- Srivastava, Saurabh, Sumit Gulwani, and Jeffrey S. Foster. From program verification to program synthesis. POPL 2010.

- Jha, Susmit, et al. Oracle-guided component-based program synthesis. ICSE 2010.

- Gulwani, Sumit. Automating string processing in spreadsheets using input-output examples. POPL 2011.

- Phothilimthana, Phitchaya Mangpo, et al. "Scaling up superoptimization." ASPLOS 2016.

- Chandra, Kartik, and Rastislav Bodik. Bonsai: synthesis-based reasoning for type systems. POPL 2017.

- Bornholt, James, et al. Optimizing synthesis with metasketches. POPL 2016.

- Yaghmazadeh, Navid, et al. SQLizer: query synthesis from natural language. OOPSLA 2017. **Distinguished Paper Award**

- Deepcoder: Learning to write programs. Matej, et al. ICLR'16.

- Helgi Sigurbjarnarson, James Bornholt, Emina Torlak, and Xi Wang. Push-Button Verification of File Systems via Crash Refinement. OSDI 2016. **Best Paper Award**

- Shaon Barman, Sarah E. Chasins, Rastislav Bodik, Sumit Gulwani. Ringer: web automation by demonstration. OOPSLA 2016.

- Luke Nelson, Jacob Van Geffen, Emina Torlak, and Xi Wang. Specification and verification in the field: Applying formal methods to BPF just-in-time compilers in the Linux kernel. OSDI 2020.

- Chenming Wu, Haisen Zhao, Chandrakana Nandi, Jeff Lipton, Zachary Tatlock, Adriana Schulz. Carpentry Compiler. SIGGRAPH ASIA 2019.

- Permenev, Anton, et al. Verx: Safety verification of smart contracts. 2020 IEEE Symposium on Security and Privacy 2020.

- Chenglong Wang, Yu Feng, Ras Bodik, Alvin Cheung, Isil Dillig. Visualization by Example. POPL'2020.

- Beckett, Ryan, et al. Network configuration synthesis with abstract topologies. PLDI'2017.

- Dai, Wang-Zhou, et al. Bridging machine learning and logical reasoning by abductive learning. NIPS'2019.



# Academic Integrity
- Cheating WILL be taken seriously. It is not fair toward honest students to take cheating lightly, nor is it fair to the cheater to let him/her go on thinking that cheating is a reasonable alternative in life.
- The following is not considered cheating:
   - discussing broad ideas about programming assignments in groups, without being at a computer (with code-writing and debugging done individually, later).
- The following is considered cheating:
   - discussing programming assignments with someone who has already completed the problem, or looking at their completed solution.
   - looking at anyone else’s solution
   - Previous versions of the class.
   - leaving your code (for example in an online repository) visible to others, leading others to look at your solution.
   - receiving, providing, or soliciting assistance from unauthorized sources during a test.
- Programming assignments are not intended to be grade-makers, but to prepare you for the tests, which are the grade-makers. Cheating on the programming assignment is not only unethical, but shows a fundamental misunderstanding of the purpose of these assignments.
- Penalties: First time: a zero for the assignment; Second time: an “F” in the course.

