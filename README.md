Space and time comlexity 

MinMax Sum: because there is a sorting operation in the code, the run time complexity would be O(nlog(n)). 
Space Complexity: O(1)

Weighted uniform strings:
Time Complexity

We are iterating through teh string s once to calculate the weights.The function then iterates over each query in the queries list. If there are q queries, and checking if an element exists in a HashSet is O(1), this part has a time complexity of O(q).

The overall time complexity is the sum of these parts, which is O(n + q)
Te space complexity is thus also O(n + q)

