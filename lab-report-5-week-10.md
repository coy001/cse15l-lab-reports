# **Lab Report 5**

### **1.How to find different results**

I used vimdiff to implement
### **2.Provide a link to the files**

[testfile194](https://github.com/coy001/my-markdown-parser/blob/main/test-files/194.md)

[testfile201](https://github.com/coy001/my-markdown-parser/blob/main/test-files/201.md)

### **3.Picture of vimdiff command**

![image](https://user-images.githubusercontent.com/103301184/172476469-e28a9e4a-9751-4124-9b3c-b2a117fb211c.png)

### **4.Expected output and whether implement correct**

I.Neither are correct in this situation.

The Expected for testfile201 is [my_(url)]

a.But my result is [].

My Code:

![image](https://user-images.githubusercontent.com/103301184/172481208-1dc89dab-1acc-4ad9-839e-14dfb42f4343.png)

My Bug:The file actually refers to the link my_(url), but the code I implemented only dicide the result with a brackets and parens. Therefore, my code did not get any link from the file since it does not have a pair of brackets.

b.Given Result is [url]

Given Code:

![image](https://user-images.githubusercontent.com/103301184/172484508-210342a9-b4ed-4e8a-99b3-39451deac1ac.png)

Given Bug: The given code only consider "(" or ")" after "]", but not necessaryly require "[". Therefore, the given code would get the content in the "()" that after "]". Which the content is url.


II.The given code is correct and my code is wrong

The Expected for testfile201 is [baz]

a. But my result is []

My Code:

![image](https://user-images.githubusercontent.com/103301184/172485715-4bdbefe6-e8cc-4917-b4ed-e52765bb2785.png)

Bug:My code does not consider about the situation that brackets and parens that does not connect to each other

b.The given code succesfully get that [baz], the same with expected.

Given Code:

![image](https://user-images.githubusercontent.com/103301184/172486535-b6ebbe7a-6516-4e05-b6df-15850bd05fc8.png)

Given does not have bug in this case.



