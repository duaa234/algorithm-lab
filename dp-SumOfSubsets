#include <stdio.h›
#include <stdbool.h>
solution
// Returns true if there is a subset of setil
// with sum equal to given
sum
bool
isSubsetSum(int set[l, int, int sum)
The value of subset (i]lil
will be true if
there is a subset of setlo..j-1] with sum equal to i
bool
subsetin + 11[sum + 11;
// If
sum is 0, then answer
for (int
i = 0; i <= n;
i++)
subset (il l0] = true;
is
true
// If sum is not 0 and set is empty,
// then answer is false
for
(int i = 1; i <= sum; i++)
subset (0]li] = false;
/Fill
the subset table in bottom up
manner
for (int
i = 1; i <= n; i++) 0
for
(int j = 1; j <= sum; j++) 0
if j< setli = 10）
subset (illjl = subsetli - 11 lil;
i£
(j >= set (i - 11)
suoset［iJlj
subset (i - 10(51
Il subset li - 1llj - setli - 110;
037
return subset (n] [sum];
// Driver code
int main ()
int int int
set ll = ( 3, 34, 4, 12, 5, 2 };
sum = 9;
n = sizeof (set) / sizeof (set (0]) ;
if (isSubsetSum (set, n, sum) == true)
printf ("Found a subset with given sum") ;
else
printf ("No subset with given sum");
}