# Notes on the Midterm

* _Correctness    (out of 40):_ 39
* _Good Practices (out of 10):_ 10
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._



## Step 1
* Easy to understand and you had good docstrings.

## Step 2
* Here, your code assumes that the `allowed_amount` will never be 0. That isn't a safe assumption. If there were any items with an `allowed_amount` of 0, your code would return None as if the item didn't exist. I've deducted 1 point from _Correctness_ for this.

## Step 3
* Nice job reusing your `get_rate()` function.
* I also like how you created three conditions to match the requirements literally, even though it could have been logically simplified. I think this is better for traceability.

## Step 4
* Nice work. Easy to understand and follow.