# Q5    import re

raw = """
[Paste all numbers from all tables here]
"""
nums = list(map(int, re.findall(r'\d+', raw)))
total = sum(nums)
print(total)               
ans is 3926312
     
