# Lab Report 4

My code implementation: [My MarkdownParse](https://github.com/soph-song/markdown-parser)

Code implementation I reviewed week 7: [Reviewed MarkdownParse](https://github.com/mrreganwang/markdown-parser)

---
## Expected Outputs using VScode preview
1. Code Snippet 1 

![image](.\images\snippet1EO.png)

Expected Output: [`google.com, google.com, ucsd.edu]

2. Code Snippet 2

![image](.\images\snippet2EO.png)

Expected Output: [a.com, a.com(()), example.com]

3. Code Snippet 3

![image](.\images\snippet3EO.png)

Expected Output: [https://sites.google.com/eng.ucsd.edu/cse-15l-spring-2022/schedule]

---
## Test Code Snippets
First screenshot is my implementation, second is reviewed implementation.
1. Output of Code Snippet 1 

my implementation:
![image](.\images\output1.png)

reviewed implementation:
![image](.\images\Routput1.png)

2. Output of Code Snippet 2 

my implementation:
![image](.\images\output2.png)

reviewed implementation:
![image](.\images\Routput2.png)

3. Output of Code Snippet 3

my implementation:
![image](.\images\output3.png)

reviewed implementation:
![image](.\images\Routput3.png)

---

## Possible Code Change

1. Code Snippet 1:
This would be a small code change where I have to set up an if statement case to check if there's an "`" in front of the open bracket. If there is, then I can skip to the next open bracket and find our next link.

2. Code Snippet 2:
I feel like this would be a more involved change given the complexity of the case. In fact, I think it would take a structure change to accomodate for this situation because my code works by keep on finding the next symbols. However, I think for the code to work, I'd need to keep track of parenthesis and brackets pairs.

3. Code Snippet 3:
I feel like this would be a small code change where I have to check for line breaks or new lines within the brackets and parenthesis. If there's a line break, then I can skip to the next open bracket and find the next possible link.