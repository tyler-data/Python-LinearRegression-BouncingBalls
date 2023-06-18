# 🏀 Linear Regression - Bouncing Balls

In this project, we're whipping up a linear regression model from scratch in Python, with the aim of making a ball pit even more fun at a local fast food joint 🍔. By bouncing balls of different sizes and recording the bouncy results, we have data to play with 📈. This data helps us use linear regression to understand the intriguing relationship between a ball's size and its bounciness. 

This project is a wild ride over several parts:

## Part 1: Calculating Error 📐

First off, we're tackling the task of calculating the difference between the real deal and our predictions 🧐. We start with a function `get_y(m, b, x)` that returns the y value for a given x on our line (defined by the slope `m` and intercept `b`). From there, we calculate the error between a data point and a line with `calculate_error(m,b,point)`. Finally, `calculate_all_error(m,b,points)` sums up all these errors for a line across all data points.

## Part 2: Trying Out Slopes and Intercepts 🎢

In this stage, we're going on a hunt for the line of best fit 🎯. We do this by taking a shot at different slopes and intercepts, and picking the ones that minimize our error function. This involves creating a list of potential `m` (slope) and `b` (intercept) values, and checking the total error for each possible line.

## Part 3: Model Prediction 🔮

Once we've found our line of best fit (thanks to our slope `m` and intercept `b`), we're ready to make some predictions on new data 🆕. For example, we can predict the bounciness of a new ball size using our line of best fit.

Throughout this project, we use examples and tests to make sure our functions are running like clockwork ⏰. We check that our error calculations are accurate and that our method for finding the best fit line really hits the mark. This project offers a solid foundation in understanding linear regression and its power to make predictions from data.
