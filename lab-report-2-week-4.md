# **Lab Report 2**
### **1.The screenshot of change diff on github**

I.change 1:break from while loop(get rid of those deletions)

![image](https://user-images.githubusercontent.com/103301184/166409188-a6e80a6f-8c3b-407f-965a-e2d4c166c92c.png)

II.add a inner while, to solve problem if the link contains "(" ")" "[" "]"

![image](https://user-images.githubusercontent.com/103301184/166409490-28f8303c-5ec1-40f6-baec-f7ac926e5737.png)



### **2.Linked to the test file**


### **3.The screenshot of symptoms and error**

Symptom1: Infinite while

![image](https://user-images.githubusercontent.com/103301184/166410028-f5c5efcb-7033-414e-a56a-e8d6515c7343.png)

Symptom2:

![image](https://user-images.githubusercontent.com/103301184/166410390-a6a8d389-0d58-4c4e-865e-ad399547b5a1.png)

Symptom3:




### **4.The reflection about symptoms**
Symptom1

The symptom is caused because the while loop does not terminated. Therefore, adding some statement "if()" to determine whether "(", ")","[","]" is detected; if not detected, then return toReturn to terminate the while loop.

Symptom2

Some links contain "(" ")" and the name "[" "]", we should use a while loop to ensure get the right link

Symptom3

