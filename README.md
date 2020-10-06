             Pros and Cons of Using an Array

            Adding an entry to the bag is fast
    • Removing an unspecified entry is fast
    • Removing a particular entry requires time to locate the entry
    • A fixed-size array is limited in its capacity
    • Approaches to dynamically increase the size of the array are possible (but increasing the size
    of the array requires time to copy its entries)
    
    
    • Longest Common Subsequence
    Challenge
    • In the application created in this exercise, two strings of characters will be taken as input and
    the longest subsequence of characters common to both strings will be determined. We want
    to find the longest sequence of letters that is common between two strings.
    • For one string to be a subsequence of the other, all letters in the first string must match up
    uniquely with a letter in the second string.
    • The matches have to be in the same order, but they do not need to be consecutive. For
    example, “WBCAX” is a subsequence of “ZWABCEFAABX” as can be seen below
