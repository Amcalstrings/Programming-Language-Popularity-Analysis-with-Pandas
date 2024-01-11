

To figure out which Programming language is the most popular based on number of posts on Stack overflow:

1. used .groupby() to explore the number of posts and entries per programming language

2. converted strings to Datetime objects with to_datetime() for easier plotting

3. reshaped our DataFrame by converting categories to columns using .pivot()

4. used .count() and isna().values.any() to look for NaN values in our DataFrame, which we then replaced using .fillna()

5. created (multiple) line charts using .plot() with a for-loop

6. styled the charts by changing the size, the labels, and the upper and lower bounds of the axis.

7. added a legend to tell apart which line is which by colour

8. smoothed out our time-series observations with .rolling().mean() and plotted them to better identify trends over time.
