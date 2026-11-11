Issue 1:
Date not showing correctly, showing as ###
Solution: extend column size to fit each data automatically 

Issue 2:
Row 42, not capitalized data like how it's for others, it will be treated as an extra value, not as same one
Solution: automatically camelcase each value of the column

Issue 3: redundant values, item date price city all same
Solution: code checks for redundancy, if all same then removes the copy 

Issue 4: missing price row 7
Solution: TBD
Issue 5:  sweetner D has unusual price of 9999, seems like an error at row 32