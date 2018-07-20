Add your answers to the Algorithms exercises here.

1.

a) O(1)

b) O(1)

c) O(n^4)

d) O(n^2)

e) O(n^5)

f) O(n)

g) O(n)

2.

a) a = [100,22,13,24,35,46]
    maxed = 0
    for j in range(len(a)):
    for i in range(len(a)-1):
        if j >= i:
            diff = a[j] - a[i]
            if maxed < diff:
                maxed = diff

b) 



3.

a) O(n) because it'll only check the elements greater than the pivot.

b) O(n^2) it'll have to check the elements less than and greater than the pivot.
