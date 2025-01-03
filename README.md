# Leetcode-Pandas
 "Solutions to LeetCode problems using Pandas in Python."
import pandas as pd
from typing import List
def createDataframe(student_data: List[List[int]]) -> pd.DataFrame:
    column=['student_id','age']
    df=pd.DataFrame(student_data,columns=column)
    print(df)
    return df
