# coin-changer

For this exercise, we will write a function to calculate the best way to make change.
For all steps, we want the fewest number of coins possible to provide the specified value.


## Step 1: Static changer

Create a function to make change in Quarters, Dimes, Nickles, and Pennies.
The amount to make change for will be provided as an integer number of cents (e.g. $0.31 will be `31`).

You must write tests to prove that your function behaves correctly.
Make sure that your tests are also testing for optimization (for example: 31 cents can be made with 1 quarter, 1 nickle, and 1 penny or 3 dimes and 1 penny).

Complete this step before moving on.

## Step 2: Configurable changer

We have received a new requirement.
Because not all registers are fully stocked, we must take a configuration of stocked coins.
The possible values of coins are the same as step 1.

In this step, you may assume that the amount will always be possible to make with the configured coins.

Complete this step before moving on.

## Step 3: Error Handling

It turns out that assuming that the amount will always be possible to make with the configured coins was a bad assumption.

In this step, add error handling so that invalid amounts are reported to the caller (for example, `31` is invalid if pennies are not part of the configuration).

Discuss what you decided to use to convey this error to the caller.
Why did you decide to use this method instead of a different method?

Complete this step before moving on.

## Step 4: Arbitrary configuration

Update the code from step 2 to accept arbitrary coin values.
Your code should be compatible with the [three-cent piece](https://en.wikipedia.org/wiki/Three-cent_piece) and the [double dime](https://en.wikipedia.org/wiki/Twenty-cent_piece_(United_States_coin))

Add tests to ensure that this change is compatible with the error handling you added in step 3.