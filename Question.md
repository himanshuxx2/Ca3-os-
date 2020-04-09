# Ca3-os-
Operating system Assignment 

Ques. 21. Consider a scenario of demand paged memory. Page table is held in registers. It takes 8 milliseconds to service a page fault if an empty page is available or the replaced page is not modified and 20 milliseconds if the replaced page is modified. Memory access time is 100 nanoseconds. Assume that the page to be replaced is modified 70 percent of the time. Generate a solution to find maximum acceptable page-fault rate for access time that is not more than 200 nanoseconds.

Ans- 

Here we have to find an effective access time (EAT) for a given page-fault rate. 
so we have to solve for 'p':
Time taken to service page Fault for empty page or unmodified page = 8ms.
Time taken to service page Fault for modified page = 20ms
Memory access time = 100ns
EAT = 200ns
      EAT = (1-p)*(100) + (p)*(100 + (1-.7)*(8msec) + (.7)*(20msec))   
	  = 100 - 100p + 100p + (2.4e6)*p + (14e6)*p
	  = 100 + (16.4e6)*p
      200 = 100 + (16.4e6)*p
      p = 100/16.4e6 = 6.0976 apx...



