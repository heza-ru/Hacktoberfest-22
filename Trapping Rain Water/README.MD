# Leetcode Problem 42 :  [Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)
### Level : HARD
<hr/>

### Statement:
Given n non-negative integers representing an elevation map where the width of each bar is 1, compute how much water it can trap after raining.


**Example 1:** <br/>
![image](https://user-images.githubusercontent.com/114819385/193426225-4ca873fa-72cb-43db-8185-303fc1144df9.png)

Input: height = [0,1,0,2,1,0,1,3,2,1,2,1]<br/>
Output: 6<br/>
Explanation: The above elevation map (black section) is represented by array [0,1,0,2,1,0,1,3,2,1,2,1]. In this case, 6 units of rain water (blue section) are being trapped.


**Example 2:**
Input: height = [4,2,0,3,2,5]<br/>
Output: 9<br/>
 

### Constraints:

n == height.length<br/>
1 <= n <= 2 * 104<br/>
0 <= height[i] <= 105<br/>
