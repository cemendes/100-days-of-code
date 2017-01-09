# 100 Days Of Code - Log

### Day 0: January 3rd, 2017

**Today's Progress**: None.

**Thoughts:** None

### Day 1: January 4th, 2017

**Today's Progress**: None.

**Thoughts:** None

### Day 2: January 5th, 2017

**Today's Progress**: None.

**Thoughts:** None

### Day 3: January 6th, 2017

**Today's Progress**: None.

**Thoughts:** None

### Day 4: January 7th, 2017

**Today's Progress**: Worked on check_tomcat-logs script. Implemented lists and for loop using lists in bash. Trying to define the server lifecycle. 

**Thoughts:** Lists in bash are not as straigthfoward as in python. 

### Day 5: January 8th, 2017

**Today's Progress**: Worked on check_tomcat-logs script. I was able to fix the kill and trap issue. 

**Thoughts:** It was interesting to see that pkill and kill do not behave in the same way with trap. Only kill triggered trap, not pkill. I wonder if this is fixed in a newer version of bash, kill or pkill. I tested it on RHEL 6.6. Then, I tested it on RHEL 7.2 and the behavior is also erratic there. It seems that one needs to use kill when using trap. 
