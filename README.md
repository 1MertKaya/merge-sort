# Merge Sort Project - www.patika.dev

Our array is: [16,21,11,8,12,22]

1. Begin with seperating the array into two parts as [16, 21, 11] and [8, 12, 22].
2. Seperate the parts again into two parts as [16] -- [21, 11] --- [8] -- [12, 22].
3. Now seperate again to create 6 different arrays: [16] -- [21] - [11] --- [8] -- [12] - [22].
4. Start to merge as lower number of dashes comes first: [16] -- [11, 21] --- [8] -- [12, 22].
5. Continue merging: [11, 16, 21] and [8, 12, 22].
6. As the last step, merge these two parts: [8, 11, 12, 16, 21, 22].

## Big-O Notation
- 2^x=n -> logn
- O(n.logn) -> *6.log6*
