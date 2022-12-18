# Day1_Additive-equivalent

arr=list(map(int,input().strip().split()))

k=int(input())

len1=len(arr)

for i in range(0,len1):

    for j in range(1,len1):

        if((arr[i]+arr[j])==k):

            print("True")

    break
