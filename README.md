# Square-Root-Generator
This circuit generates the floor of square root of the given 10-bit number. 
# Approach
I have employed binary search algorithm to perform this task.
Algorithm:
Three registers st,end,and ans are initialized as
st = 0;
end = 31;
ans = 0;
while(end>=st)
{
  mid = (st+end)/2;
  if(mid*mid==given)
  ans = mid and stop.

  else if(mid*mid>given)
  end = mid-1;

  else 
  st = mid + 1; and ans = mid;
  
}

# Implementation
Basic Elements used or created to implement above algorithm are
1. Counter and Flip Flops
2. Square Generator Circuit (created).
3. Adders and Comparators
4. Registers.
