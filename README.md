# Hobbits-Orcs-Tom
# Problem inspired / created by UNK Artificial Intelligence class
Orcs, Hobbits, and Tom Bombadil
There are n-1 Orcs and n Hobbits who want to cross a river. We also have Tom Bombadil
who wants to cross as well. Only Hobbits and Tom Bombadil can row the boat (don’t ask
me why!) At all times, the number of Hobbits on either side of the river must be greater or
equal the number of Orcs on that side (unless there are no Hobbits on that side), or the
Hobbits will be killed by the Orcs!
- If the boat holds 2, with n=4 or more, the problem has no solution.
- If the boat can hold 3, then up to n=5 can be solved.
- If the boat can hold 4, any number (n) Hobbits can cross.
- So -- if n = 1,2 or 3 - use a boat of size 2.
- If n = 4 or 5 - use a boat of size 3.
- If n > 5 use a boat of size 4.
- If n <0 invalid inp
