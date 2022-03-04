# 1707_BipartiteGraph

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/1707_BipartiteGraph/blob/main/1707_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , BipartiteGraph , bfs.

## What was the key point and the hard part?

To find out BipartiteGraph (R-B graph) , we have to check node with depth.

Make all visit array as -1.

Starting from first node we set that node as 0 (To use %2 operation to make only 2 number (0, 1)).

Doing bfs , we color node as (depth %2) number. 

If next visiting node is already visited (!= -1) and color is same with current node, it means it is not BipartiteGraph.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
