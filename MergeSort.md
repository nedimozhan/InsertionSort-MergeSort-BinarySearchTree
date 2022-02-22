# Merge Sort Project

## [16,21,11,8,12,22] -> Merge Sort

## Merge Sort Steps :
    [16,21,11,8,12,22] 
    [16,21,11] - [8,12,22]
    [16,21] - [11] - [8,12] - [22]

    [16] - [21] - [11] - [8] - [12] - [22]
    
    [16] - [11,21] - [8] - [12,22]
    [11,16,21] - [8,12,22]
    [8,11,12,16,21,22]

## Merge Sort Big-O Notation : 
    We process n times at each steps -> O(N)
    And we do this process log(N) time
    So our algorithm works O(N Log(N))



    
