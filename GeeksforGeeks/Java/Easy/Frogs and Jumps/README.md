# 📝 Frogs and Jumps (GeeksforGeeks)

🔗 [Problem Link](https://www.geeksforgeeks.org/problems/frogs-and-jumps--170647/1)

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-brightgreen) ![Language](https://img.shields.io/badge/Language-Java-blue)

### 💡 Tags
Arrays, sieve

### 🚀 Performance
- **Runtime:** Successfully Evaluated
- **Memory:** N/A

---

### 📜 Problem Description

Frogs are positioned at one end of a pond, and each wants to reach the other end. The pond has some leaves arranged in a straight line.

Each frog has a strength  **s** , meaning it jumps exactly  **s** leaves at a time - for example, a frog with strength 2 visits leaves 2, 4, 6, and so on while crossing the pond.

Given the strength of each frog (as an array  **arr[]** ) and the total number of leaves  **k** , find how many leaves are not visited by any frog after all frogs have crossed the pond.

**Examples:**

```
Input: arr[] = [3, 2, 4], k = 4
Output: 1
Explanation: Frog with strength 3 visits leaf 3. Frog with strength 2 visits leaves 2, 4. Frog with strength 4 visits leaf 4. Leaf 1 is never visited by any frog.
```

```
Input: arr[] = [1, 3, 5], k = 6
Output: 0
Explanation: Frog with strength 1 visits leaves 1, 2, 3, 4, 5, 6 every leaf. All leaves are already covered, so none are left unvisited.
```

**Constraints:** 
1 ≤ n, k, arr[i] ≤ 105