

## Criteria for a function to get tot badge

1. Its survival time should be above a threshold (365 days at the time of creating this repo).
2. Dev Eq of its firt commit should be above a threshold (25 at the time of creating this repo).
3. The sum of Dev Eq of subsequent commits should be less than 10% of that of the first commit.
4. It calls or gets called by some other functions (in-degree + out-degree > 0).

## Test cases

1. This readme file is added by the second commit, which is more than 1 year later than the first commit. What this commit does is irrelevant, we just need this commit there to refresh the end time used in calculating survival length. 

