# -Write-a-program-to-find-all-pairs-of-integers-whose-sum-is-equal-to-a-given-number
Python programming

def FindPair(list,sum):
    for i in range(len(list)):
        for j in range(i-1,len(list)):
            if (list[i]+list[j])==sum:
                print(list[i],list[j])
FindPair(mylist,30)           
    
