# Python-Infinite-Loop
 In this project, we'll explore how to use Python threading to create a simple program that prints "aaaaaa" and "bbbbbb" simultaneously. It's a fun way to demonstrate the power of multithreading and can be a starting point for more complex projects.

# Preview

https://github.com/neelay-16/Python-Infinite-Loop/assets/135517502/07c010d9-cffb-4dbf-915b-e2621d2c4ff1


# Description

Importing the threading module. This line imports the threading module, which provides a way to work with threads in Python.

![image](https://github.com/neelay-16/Python-Infinite-Loop/assets/135517502/f93e2a57-ec3a-4f14-b6cd-80e12fcd86e1)


Defining the lwa function. Here, lwa is a function that contains an infinite loop. Inside the loop, it repeatedly prints the string "aaaaaa" to the console.

![image](https://github.com/neelay-16/Python-Infinite-Loop/assets/135517502/0d7d71ae-ec51-4bd2-aa25-2f0174819298)


Similar to lwa, the lwb function also has an infinite loop that prints the string "bbbbbb" to the console repeatedly.

![image](https://github.com/neelay-16/Python-Infinite-Loop/assets/135517502/074edeed-b6d0-4186-815d-ef40285fb453)

Creating two threads 'thread_a' and 'thread_b'.Each thread is associated with one of the previously defined functions, lwa and lwb, using the target parameter. This prepares the threads to execute those functions concurrently.

![image](https://github.com/neelay-16/Python-Infinite-Loop/assets/135517502/842c0d02-b499-4b89-bf44-1230ba677c18)

The start() method is called on both thread_a and thread_b to begin their execution. This is where the concurrency comes into play. Once the threads are started, they will independently execute the lwa and lwb functions concurrently.

![image](https://github.com/neelay-16/Python-Infinite-Loop/assets/135517502/e77e78cf-0fdf-4b5c-8d34-e56ca5b6ba82)



You should see "aaaaaa" and "bbbbbb" alternating in your console, demonstrating the simultaneous execution of both threads.

Feel free to experiment and modify the code as you like. This project serves as a basic example of Python threading, and you can extend it to create more complex multithreaded applications.





