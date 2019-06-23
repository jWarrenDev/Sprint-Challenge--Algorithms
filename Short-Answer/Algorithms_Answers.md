Add your answers to the Algorithms exercises here.

Exercise: I

a)  The runtime is Linear with respect to n.  I think that it is O(n)

b) The runtime for this function has multiple for loops.  This is most likely an iterative approach which means the we have to walk through each array. As walk through each array this the runtime will mostly likely be notated as O(n^3).  

c)  This fuction takes a recursive approach with no range defined.  Also this is a step down approach as defined in the return (n-1), which means that it creates a stack and them collapses them. I think that the notation for this is O(2n) == O(n). I'm not sure. 

Exercise: II

First of all.. i have an unlimited range.  I do not know how many n's the building has.  However, I do know that if I am BELOW f, then no eggs will be safe. 


Proposed Algorithm:

I know that if i'm below f then eggs are defintiely safe.  So I want to make a case that no matter what n is, f is the limiting factor. 

Not sure how to write this.. but... 

safe = f > n

def safeEggs(n):;
    if n < f 
        return n

    return safeEggs(n-1)

I'm not sure.  But this looks like a recursive so I would say O(2n) again.  The fastest way would be a log (n) approach using a binary search. 