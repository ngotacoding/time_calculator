# Time Calculator

This is the boilerplate for the Time Calculator project. Instructions for building your project can be found at: <https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/time-calculator>

## Problem

You will be working on this project with our Replit starter code.

Write a function named **add_time** that takes in *two required parameters and one optional parameter*:

1. a start time in the 12-hour clock format (ending in AM or PM)
1. a duration time that indicates the number of hours and minutes
1. (optional) a starting day of the week, case insensitive
1. The function should add the duration time to the start time and return the result.

- If the result will be the next day, it should show (next day) after the time. If the result will be more than one day later, it should show (n days later) after the time, where "n" is the number of days later.

- If the function is given the optional starting day of the week parameter, then the output should display the day of the week of the result. The day of the week in the output should appear after the time and before the number of days later.

### Below are some examples of different cases the function should handle. Pay close attention to the spacing and punctuation of the results

```Python
add_time("3:00 PM", "3:10")
# Returns: 6:10 PM
```

```Python
add_time("11:30 AM", "2:32", "Monday")
# Returns: 2:02 PM, Monday
```

```Python
add_time("11:43 AM", "00:20")
# Returns: 12:03 PM
```

```Python
add_time("10:10 PM", "3:30")
# Returns: 1:40 AM (next day)
```

```Python
add_time("11:43 PM", "24:20", "tueSday")
# Returns: 12:03 AM, Thursday (2 days later)
```

``` Python
add_time("6:30 PM", "205:12")
#Returns: 7:42 AM (9 days later)
```

**Do not import any Python libraries. Assume that the start times are valid times. The minutes in the duration time will be a whole number less than 60, but the hour can be any whole number.**

### Development

Write your code in time_calculator.py. For development, you can use main.py to test your time_calculator() function. Click the "run" button and main.py will run.

### Testing

The unit tests for this project are in test_module.py. We imported the tests from test_module.py to main.py for your convenience. The tests will run automatically whenever you hit the "run" button.

### Submitting

Copy your project's URL and submit it to freeCodeCamp.