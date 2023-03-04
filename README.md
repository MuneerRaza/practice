
# Assignment 01

Student Name: Muneer Raza

Student ID: 21k-3084

Making a custom kernel with custom 'hello world' system call

### STEPS
Installing pre requisites

![1](https://user-images.githubusercontent.com/107882873/222903384-8c88c55c-0cb5-4ac1-a493-d43cffface4c.png)

Switching to root user

Making kernels directory

Downloading kernel version(4.19.275)

Extracting the downloaded kernel

![2](https://user-images.githubusercontent.com/107882873/222903434-25de18c2-47fe-4f2d-8422-f6742ede9dcb.png)

Making hello directory

Writing C program hello.c (program for system call)

![3](https://user-images.githubusercontent.com/107882873/222903604-9bf20b1c-9add-41c5-aa85-635c2ffb2d7a.png)
![4](https://user-images.githubusercontent.com/107882873/222903618-9d904b0f-7679-4428-a9e8-0eba5f6e61b2.png)

Making 'Makefile' for Above C program

![5](https://user-images.githubusercontent.com/107882873/222904304-c9e5c2b1-8ffc-4df2-8562-110f8841b518.png)

Adding above program to system table file

![6](https://user-images.githubusercontent.com/107882873/222904413-ddb092b3-2777-4a18-b860-476e45fed4b9.png)

Adding the prototype of the new system call into the system calls header file

![7](https://user-images.githubusercontent.com/107882873/222904503-c23a72fe-a5f7-4c10-bbce-8c2d6bea9c35.png)

Changing Kernel version name

![8](https://user-images.githubusercontent.com/107882873/222904533-828febe7-a53a-484f-90f5-3ad626d7803d.png

Adding the hello folder in the kernel’s Makefile

![9](https://user-images.githubusercontent.com/107882873/222904628-5611268f-a089-4a03-a263-8b3fabb5af89.png)

Copying old config file to new kernel folder

![10](https://user-images.githubusercontent.com/107882873/222904672-282d2471-fd5b-427f-9335-050f63e82c64.png)

Setting Configuration parameter

![11](https://user-images.githubusercontent.com/107882873/222904873-fd91fdc7-4648-494e-81df-1ac140fe6e32.png)

Cleaning intermediate temporary files

Creating bootable image fot this(new downloaded) kernel

![12](https://user-images.githubusercontent.com/107882873/222905054-21fe181c-95c9-4d80-a0d9-bef4ad9ae6e9.png)
![13](https://user-images.githubusercontent.com/107882873/222905486-0c0f3089-89c0-4489-9974-aa1e54e643f3.png)

Installing kernel Image into boot directory

![14](https://user-images.githubusercontent.com/107882873/222905616-d775178b-f3d1-4e0d-b138-67453f33967f.png)
![15](https://user-images.githubusercontent.com/107882873/222905599-094825da-3926-48d6-a36b-73c849c870e7.png)

Updating Grub

![16](https://user-images.githubusercontent.com/107882873/222905637-de5da4d7-04fd-4000-a119-79c2a79b622c.png)

Writing C program for checking the output of our hello world system call
![18](https://user-images.githubusercontent.com/107882873/222905679-31adce2c-bcb6-4775-88a8-2860083cc368.png)

Output

![19](https://user-images.githubusercontent.com/107882873/222905697-bfa54fb6-bf3d-428f-b530-d19c4388741b.png)
![20](https://user-images.githubusercontent.com/107882873/222905701-36c5d16b-1149-4075-88d5-606390534717.png)
