# bash-challenges

1st Question

a. Display the path of your current directory:

![image](https://user-images.githubusercontent.com/121697755/227755025-cb43084e-8d3a-43c3-853e-d28d59870556.png)

b. List out the contents of your current directory

![image](https://user-images.githubusercontent.com/121697755/227755043-cbe99cb5-b1ab-4bf0-8341-be963d4c9ef6.png)

c. List out the contents of your current directory including hidden files

![image](https://user-images.githubusercontent.com/121697755/227755051-29907094-68a1-4ecc-9814-160e54988633.png)

------------

2nd Question

a. Create a new directory named a

![image](https://user-images.githubusercontent.com/121697755/227755538-360e3748-a456-46fc-b1b2-d88880f65971.png)

b. Move to the newly created directory a 

![image](https://user-images.githubusercontent.com/121697755/227755544-9db7677d-b26d-4673-9138-8219753b8acd.png)

c. Create a blank file named “file1”

![image](https://user-images.githubusercontent.com/121697755/227755558-d92a73b2-7932-4e7d-9406-3e3e0bdc6abe.png)

d. Display the file type of “file1”

![image](https://user-images.githubusercontent.com/121697755/227755717-5d06ee1d-5b55-42e3-9ede-b256c6a65f37.png)

e. Add the line “Hello World” to “file1” using the command echo

![image](https://user-images.githubusercontent.com/121697755/227756256-c1ed9eed-5865-4db4-b982-80b0970b8a2c.png)

f. Display the contents of “file1” 

![image](https://user-images.githubusercontent.com/121697755/227756246-938e8947-5721-423b-8ffa-683c6da67d95.png)
#we could also use less command to display contents of the file in a controlled manner. The less view could be quit using the key "q"

g. Display the file type of “file1” again 

 ![image](https://user-images.githubusercontent.com/121697755/227756277-80b601ef-7183-47de-a8de-c0eb76d1c03c.png)

------------

3rd Question

a. Stay in directory a. Create a file “file2” and add the contents below using the  command cat 
First Line Second Line Third Line 

![image](https://user-images.githubusercontent.com/121697755/227756551-ae7bee61-a031-4c5c-895e-2b622c60fe9d.png)
use ctrl + d to save changes and exit cat appending.

b. Display the contents of “file2” 

![image](https://user-images.githubusercontent.com/121697755/227756599-3a4bd6a3-ff21-4132-86a7-ff2eea117923.png)

c. Display the contents of “file2” with the lines reversed

![image](https://user-images.githubusercontent.com/121697755/227756848-b5ddf29b-6f8f-4564-bf59-34ab7eac61d7.png)

------------

4th Question

a. Stay in directory a. Concatenate the contents of “file1” and “file2” and save them into a new file “file3” 

![image](https://user-images.githubusercontent.com/121697755/227756890-2ba19d5b-3a18-4974-9e2b-98b0ccb61b8c.png)

b. Display the contents of “file3” 

 ![image](https://user-images.githubusercontent.com/121697755/227756911-53db1738-8356-4304-a7c1-fc2356997950.png)

------------

5th Question

a. Stay in directory a. Create 2 directories b/c with a single command  

![image](https://user-images.githubusercontent.com/121697755/227757048-b00a98bd-d176-4100-b02f-30b11c7e2422.png)

b. Create a new directory d 

![image](https://user-images.githubusercontent.com/121697755/227757117-38c1b6ad-296c-43fe-ad5e-5fcb127576de.png)
![image](https://user-images.githubusercontent.com/121697755/227757136-14849c7e-f4f0-42a2-bc9c-6cbe12df0792.png)


c. Copy the directory d to directory c using a single command 

#cp -r d c

d. Delete the directory d in the current directory a 

rmdir d

e. Copy “file3” to the directory d with a single command 

cp -r file3 d c
