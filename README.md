# The Big Heist

## Description

- Given list of bank locations, how much money each one holds and the time it would take to rob each one.
- NP hard-algorithm-1 to make as much profit as possible! (with "for" loop)
- NP hard-algorithm-2 to make as much profit as possible! (with "KNN")
- The list of banks is in `data/bank_data.csv`.
- **24 hours** to make as much money as possible and then escape.

## Rules

- Start anywhere on the map but it has to end at the **helicopter escape zone**: coordinates (0,0)
- If can't get to the helicopter within 24 hours, then jail is the place to go.
- Following the Traffic rules :), Traveling between banks at 30 km/h.
- Input is a pandas dataframe with the bank data. Output is a list of bank IDs in order that were robbed

## Output
- The Algorithm 1 collected a total of $6,439,300
- The Algorithm 2 collected a total of $11,356,200

## Check Your Solution

- `check_solution` function from `utils/check_solution.py` can be used to test the validity of the solution and obtain a _score_.

![](https://media2.giphy.com/media/l41K160KBZgAxhhG8/200.gif)
