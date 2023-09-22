# I-Can-Use-Both-Hands-
# cook your dish here
import math
for _ in range(int(input())):
    l,r,m = (map(int,input().split()))
    print(math.ceil(m / l)+math.floor(m / r))
