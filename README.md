# Kernel-Programming---Implementing-Threads
First, we define a new system call to create a kernel thread, called clone() , as well as one to wait for a thread called join() . Then, we use clone() to build a little thread library, with a thread_create() , lock_acquire() , and lock_release(). 
