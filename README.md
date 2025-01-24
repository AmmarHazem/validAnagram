# Valid Anagram

## Problem Description
Given two strings `s1` and `s2`, determine if `s2` is an anagram of `s1`.

An **anagram** is a word or phrase formed by rearranging the letters of another word or phrase, using all the original letters exactly once.

## Examples

validAnagram("danger", "garden") // returns true
validAnagram("salesmen", "nameless") // returns true
validAnagram("hello", "world") // returns false
validAnagram("rat", "car") // returns false

## Solutions

### 1. Using Hash Map (Frequency Counter)
- **Time Complexity**: O(n)
- **Space Complexity**: O(n)
- **Approach**: Count frequency of characters in both strings and compare them

### 2. Using Sorting
- **Time Complexity**: O(n log n)
- **Space Complexity**: O(n)
- **Approach**: Sort both strings and compare them directly

## Implementation Notes
- The solution handles strings of different lengths by returning `false`
- Case-sensitive comparison (e.g., "A" and "a" are considered different characters)
- Empty strings of equal length are considered anagrams

## Constraints
- Input strings consist of lowercase English letters
- `1 <= s1.length, s2.length <= 5 * 10^4`

## Function Signature
```
/
@param {string} s1
@param {string} s2
@return {boolean}
/
const validAnagram = (s1, s2) => {
// Implementation
}

```

This README includes:
1. Clear problem description
2. Multiple examples
3. Two different solution approaches with their complexities
4. Implementation notes
5. Constraints
6. Function signature with JSDoc comments
