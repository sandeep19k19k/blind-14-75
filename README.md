# blind-14-75
Missing number

Method 1 : sort and check for missing number .

Time complexity : O(n logn) -> inbuilt sort function grows like that.

Method 2 : Given that we know the length of the list,

we can use little bit of maths here.

n*(n+1)//2 ->Expected sum

sum(n) -> Actual sum

but one number is missing. so , we remove actual sum from expected sum to find the missing number.

n*(n+1)//2 - sum(n)


Time complexity : O(n) bcoz that's how inbuilt sum function grows.

Space complexity : O(1) 
