 (1) Void show status (string Message)
Shows the message in the status line of the browser.
(2)Void show Document (URL)
Shows a new webpage in the brwoser, displaying the current page.
(3)Image getimage (URL)
Returns an Image object that encapsulatethe image specified by the URL.


---------------MODULE-5---------------
______Multithreaded Programming______
Java is a multithreaded programming language which means we can develop multithreaded program using JaAVA.A Multithreaded program contains two or more parts the\at can run concurrently and each pasr can handle a different task at the same time. Multithreading enables to write in away where multiple activities can proceed concurrently in the same program.
___Advantages___
1. It doesn't block the user because threads are independent and we can perform multiple operations at same time.
2. We can perform many operations together, so it saves time.
3. Threads are independent, so it doesn't affect other threads.

___Threads___
A thread is a light weight subprocess a smallest Unit of processing. It is a seperate path of execution, threads are independent, it doesn't affect threads.

___Life Cycle of a thread___
1. New
A new thread begins its life cycle in the new state. It remains in this state until the program starts the thread.
2. Run/Runnable
After a newly born thread is started the thread becomes runnable
3. Wait 
Sometimes a thread transition to the waiting state while the thread wants for another thread to perform a task. A thread transition back to the runnable state out when only when another thread signals waiting thread to continue execution.
4. Terminate (Dead)
A runnable thread enters the terminated state when it complete its task.

___Properties of thread___
1. Apartment State 
gets or Sets the apartment state of the thread.
2. Current Context
Gets the Current context in which the thread is executing.
3. Current Thread
Gets the currently running thread.
4. Js Alive 
Gets a value indicating the execution status of current thread.
5. Js Background
Gets or sets a value indicating whether or not a thread is a background thread .
___Creating a thread ___
There are two ways to create a thread,
1) By extending thread class
2)By implementing runnable interface.
-> By extending thread class
Thread class provide costructors and methods to create and perform operations on a thread.Thread class extends object class and implements object class and implements runnable interface commonly used methods are:-
*Public Void run()
This is used to perform action for a thread.
*Public void start()
stars the executionof thread .
*Public void Sleep (long ms)
Causes the currently executing thread to sleep for the specified no: of millisec.
*public void join(long millisec)
waits for a thread to die, for the specified millisecond.
*Public void stop()
This is used to sleep to stop the thread.
->By implenting
It should be implemented by any class whose instances are intended to be executed by a thread. TRunnable in/fc have only one method, named run().
Public void run() is used to perform action for a thread.

___Priority of a thread___
Each thread have a priority. Priorities are reps by a number b/w 1 & 10. In most cases thread schedules the thread according to their priority, but it is 
