## Description

Given an array of strings, produce a single string as follows:

Repeat the following steps while there is more than one string in the array:

    find the shortest string in the array (if there are several strings of the same length take the leftmost one);
    find the shortest string among the rest (if there are several strings of the same length take the rightmost one);
    extract the chosen strings from the array;
    append the result of their concatenation (the second string should be added to the end of the first string) to the right end of the array.

After the algorithm has finished, there will be a single string left in the array. Return that string.

Example

concatenationProcess(["aaa", "dd", "bbbbb"]) = "bbbbbddaaa"

    [input] array.string init
        A non-empty array of strings.

    [output] string
