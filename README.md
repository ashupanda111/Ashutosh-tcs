



CONCEPT FOR THE EGG BREAK PROBLEM:

Basically here we follow a recurssive approach like if we throw egg from x floor

If it breaks, we try remaining (x-1) floors one by one. So in worst case, we make x trials.

If it doesn’t break, we jump (x-1) floors (Because we have already made one attempt and we don't want to go beyond x attempts. Therefore (x-1) attempts are available), Next floor we try is floor x + (x-1)

Similarly, if this drop does not break, next need to jump up to floor x + (x-1) + (x-2), then x + (x-1) + (x-2) + (x-3) and so on.

So the formulae comes out to be

x + (x-1) + (x-2), then x + (x-1) + (x-2) + (x-3) ..... +1=100 by solving this we get x=13.67

so if we take the ceil value the answer comes out to be 13

Hence it should be thrown from 13 floor in case of two eggs
