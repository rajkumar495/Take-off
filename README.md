# Take-off
t=int(input()) for _ in  range(1,t+1):     n,p,q,r=list(map(int,input().split()))     z=[]     k=[]     m=[]     ab=[]     for i in range(1,n+1):         z.append(i)     f=z[p-1:n:p]     s=z[q-1:n:q]     e=z[r-1:n:r]         l=(f+s+e)     print(l)
