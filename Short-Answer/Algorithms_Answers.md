#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n)
n^2 x n = n^3
for each iteration, a is incremented by n^2. 



b)O(n log(n))
n*log(n) = nlog(n)
first for loop runs n amount of times. 
The inner loop runs log(n) times, doubled for each iteration 


c) O(n) 
run time is constant, but will be called n amount of times


## Exercise II

I will use the number of stories in the building as a variable, n, as an input. The first story to drop the egg would be n/2 and after each drop I would change the values of the possible floors to be tested next. F will be the floor depising whether the egg will be broken or not. The f value would be incremented by one. The first story, the f value will be zero. 

If the egg is broken, current floor - 1. The next floor tested would be (n -1)/2. if the egg is not broken, current floor + 1. The next floor tested would be (n + 1)/2

The runtime of this algorithmm would be O(log n) because for each iteration, the amount of floors to check would be cut in half, because I know that anything above f, where the egg breaks, the egg will still break, and anything below where the egg breaks, it will either break or not break. But once it does not break, everything below that will not break. 



