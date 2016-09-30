# evidencebasedscheduling
based on http://www.joelonsoftware.com/items/2007/10/26.html

The idea is by joel spolsky

1. Gather evidence 
break tasks up into small tasks no more then 16 hours

make a list of tasks with one estimation and one real time column per person
then calculate velocity = est/real

  
  I now fill in an excel sheet of estimation and real times, that calculates the velocity.
  import the velocities and use these as source material. for step 2


When you schedule a new thing:

1. create the tasks, and give an estimate
2. simulate the future by dividing every task estimate by random velocity of person
3. do this 100 times

plot the estimates. 
