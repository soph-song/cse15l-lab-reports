# Lab Report 5

I used vimdiff on the results.txt of running a bash for loop to find the difference between outputs. Here are two test files that demonstrated a deviation:

## [201.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md)
1. Expected output: []
![image](/images/lab5-4.png)

2. Actual outputs (left is my implementation, right is the provided):
![image](/images/lab5-5.png)
My implementation was correct, and the provided was incorrect.





## [489.md](https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/489.md)
1. Expected output: []
![image](/images/lab5-1.png)


2. Actual outputs (left is my implementation, right is the provided):
![image](/images/lab5-2.png)
My implementation was incorrect, and the provided was correct.

3. Explanation:
![image](/images/lab5-3.png)
The problem happens in this part of our implementation. We didn't account for the fact that a new line can break the link format, instead we just look for the next close paranthesis regardless if there's a line break. Therefore, we can add an if statement to check if the open and close parenthesis is on the same line. If not, then reset the loop.