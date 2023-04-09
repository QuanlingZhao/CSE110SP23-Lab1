# Quanling Zhao's Personal page for CSE110 Spring 2023

*This is my personal page for CSE110 at UCSD*

I am a fourth year computer science undergraduate at UCSD, I have experience in multiple programming languages, ML/DL and data visualization tools. Outside school courses, I like to learn the mathematical principles and theoretical foundations behind computer science, and apply them in real world applications. I am also a research assistant at UCSD System Energy Efficiency lab (SEElab) advised by Prof. Tajana Šimunić Rosing and Xiaofan Yu, my current research topics include Hyperdimensional Computing and Federated Learning under constrained and challenging scenarios.


Here is a quote that I like about computer science:
> Computer science is no more about computers than astronomy is about telescopes.

A classic heuristic search algorithms(A*) in python: 
```
// A* (star) Pathfinding
// Initialize both open and closed list
let the openList equal empty list of nodes
let the closedList equal empty list of nodes
// Add the start node
put the startNode on the openList (leave it's f at zero)
// Loop until you find the end
while the openList is not empty
    // Get the current node
    let the currentNode equal the node with the least f value
    remove the currentNode from the openList
    add the currentNode to the closedList
    // Found the goal
    if currentNode is the goal
        Congratz! You've found the end! Backtrack to get path
    // Generate children
    let the children of the currentNode equal the adjacent nodes
    
    for each child in the children
        // Child is on the closedList
        if child is in the closedList
            continue to beginning of for loop
        // Create the f, g, and h values
        child.g = currentNode.g + distance between child and current
        child.h = distance from child to end
        child.f = child.g + child.h
        // Child is already in openList
        if child.position is in the openList's nodes positions
            if the child.g is higher than the openList node's g
                continue to beginning of for loop
        // Add the child to the openList
        add the child to the openList
```
[Source](https://medium.com/@nicholas.w.swift/easy-a-star-pathfinding-7e6689c7f7b2)

A song that I like: [Check out](https://www.youtube.com/watch?v=o-YBDTqX_ZU)

[Top](#quanling-zhaos-personal-page-for-cse110-spring-2023)

Logo of my school:
![Logo](/images/logo.png)

List of classes I am interested:
+ MATH181
+ MATH142
+ CSE 150
+ CSE 199

My favorite single digit numbers:
1. 5
2. 7
3. 1

Upcoming tasks:
- [x] CSE110 lab 1
- [ ] Graduate
- [ ] More













