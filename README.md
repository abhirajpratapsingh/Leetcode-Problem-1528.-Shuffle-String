# Abhiraj Pratap Singh

---


# Intuition
<!-- Describe your first thoughts on how to solve this problem. -->
- The intuition behind the code seems to be reordering the characters in the string s based on the corresponding indices provided in the vector indices.

---



# Approach
<!-- Describe your approach to solving the problem. -->

- Certainly! Here's the approach in bullet points:

1. Input:
    - Take a string s and a vector of integers indices as input.
2. Initialization:
    - Initialize an empty string s1 to store the rearranged characters.
3. Nested Loop:
    - Use a nested loop to iterate through each character in the string s.
    - For each character, iterate through the indices vector to find the correct position.
4. Build the Result String:
    - Append the characters to the result string s1 in the order specified by the indices.
    - Break out of the inner loop once the correct position is found for the current character.
5. Return Result:
    - Return the final string s1 as the result.

---



# Complexity

---


- Time complexity:
<!-- Add your time complexity here, e.g. $$O(n)$$ -->
- **Time complexity: O(s * indices)**,* where s is the length of the input string and indices is the size of the vector.*

---


- Space complexity:
<!-- Add your space complexity here, e.g. $$O(n)$$ -->
- **Space complexity: O(s),** *as the additional space is used for the string s1.*

---
