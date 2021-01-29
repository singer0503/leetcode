<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../find-followers-count "Find Followers Count")
　　　　　　　　　　　　　　　　
[Next >](../the-number-of-employees-which-report-to-each-employee "The Number of Employees Which Report to Each Employee")

## [1730. Shortest Path to Get Food (Medium)](https://leetcode.com/problems/shortest-path-to-get-food "")



### Related Topics
  [[Depth-first Search](../../tag/depth-first-search/README.md)]
  [[Breadth-first Search](../../tag/breadth-first-search/README.md)]
  [[Graph](../../tag/graph/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Run BFS starting from the '*' position.
</details>

<details>
<summary>Hint 2</summary>
Keep the current number of the steps as a state in the queue.
</details>

<details>
<summary>Hint 3</summary>
The first time you reach a food, return the number of steps as the answer.
</details>

<details>
<summary>Hint 4</summary>
In case the queue is empty and you still did not manage to reach a food, return -1.
</details>