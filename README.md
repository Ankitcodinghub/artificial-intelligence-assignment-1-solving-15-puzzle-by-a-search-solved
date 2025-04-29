# artificial-intelligence-assignment-1-solving-15-puzzle-by-a-search-solved
**TO GET THIS SOLUTION VISIT:** [artificial-intelligence Assignment 1-Solving 15-puzzle by A* search Solved](https://www.ankitcodinghub.com/product/artificial-intelligence-solving-15-puzzle-by-a-search-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115394&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;artificial-intelligence Assignment 1-Solving 15-puzzle by A* search Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Input: The input is a text file. The first line contains an integer n which indicates there are (n-1) problems to be solved. The second line describes the goal state. The following (n-1) lines describe initial states, one initial state per line. Overall, the input file has (n+1) lines.

For this assignment, we assume the goal state is going to be the standard goal state: the integers are in consecutive order with the blank space in the bottom right corner. We also assume the blank state is described as a zero. So, the goal state is described by [1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 0]

Output: The output should show the sequence of steps from the initial state to the goal state. Two heuristics (the misplaced tiles and the Manhattan distance) should be used. The output should mention the path cost. Since both the heuristics are admissible, we would obtain the path with the same cost. To find contrast, the output should print the number of expanded nodes (the size of the closed list) during the search.

(1) https://www.cs.bham.ac.uk/~mdr/teaching/modules04/java2/TilesSolvability.html

(2) https://www.geeksforgeeks.org/check-instance-15-puzzle-solvable/

The rule for solvability (assuming the standard goal state) for 15-puzzle:

the puzzle instance is solvable if

(a) the blank is on an even row counting from the bottom (second-last, fourth-last, etc.) and the number of inversions is odd. or,

(b) the blank is on an odd row counting from the bottom (last, third-last, fifth-last, etc.) and the number of inversions is even.

An inversion occurs when a tile with a higher number precedes a tile with a lower number.

Counting inversions:

Figure-1

In the figure, X indicates the blank space. Here the sequence is 6 13 7 10 8 9 11 X 15 2 12 5 14 3 1 4.

tile-6 tile-13 tile-7 tile-10 tile-8 tile-9 tile-11 tile-15 tile-2 tile-12 tile-5 tile-14 tile-3 tile-1 tile-4

5 11 5 7 5 5 5 7 1 4 3 3 1 0 0

The total number of inversions for this initial state (figure-1) is 5 + 11 + 5+ 7+ 5 + 5 + 5 + 7+ 1 + 4 + 3 + 3+ 1 + 0 + 0 = 62

Similarly, we can determine the number of inversions for figure-2 and figure-3.

Figure-2

tile-13 tile-2 tile-10 tile-3 tile-1 tile-12 tile-8 tile-4 tile-5 tile-9 tile-6 tile-15 tile-14 tile-11 tile-7

12 1 8 1 0 7 4 0 0 2 0 3 2 1 0

The total number of inversions for this initial state (figure-2) is 12 + 1 + 8 + 1 + 0 + 7 + 4 + 0 + 0 + 2 + 0 + 3 + 2 + 1 + 0 = 41

Figure-3

tile-3 tile-9 tile-1 tile-15 tile-14 tile-11 tile-4 tile-6 tile-13 tile-10 tile-12 tile-2 tile-7 tile-8 tile-5

2 7 0 11 10 7 1 2 6 4 4 0 1 1 0

The total number of inversions for this initial state (figure-3) is 2 + 7 + 0 + 11 + 10 + 7 + 1 + 2 + 6 + 4 + 4 + 0 + 1 + 1 + 0 = 56
