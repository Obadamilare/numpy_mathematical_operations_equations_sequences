# NumPy Hands On Exercises

Industry based practice exercises applying NumPy to data summarization, variability measurement, and numerical series analysis. Built while strengthening quantitative and data analysis fundamentals ahead of more advanced Python based financial analysis work.

## Overview

* Four scenarios, each solved using core NumPy operations
* Progresses from simple aggregation, to statistical spread, to a numerical convergence problem, then closes with an independent applied challenge
* Every result is paired with a short interpretation, not just a printed number

## Exercise 1: Sales Performance Calculator

* Created a week of daily sales figures as a NumPy array
* Calculated total sales using `np.sum()`
* Calculated average daily sales using `np.mean()`
* Applied a 10% sales adjustment across the array using vectorized multiplication
* Compared adjusted sales against original sales
* Key takeaway: the total shows overall weekly revenue, the average shows what a typical day looks like, which is more useful for staffing and stock decisions since a single strong day can inflate the total

## Exercise 2: Student Performance Analysis

* Built a dataset of test scores as a NumPy array
* Calculated the mean score
* Calculated each student's deviation from the mean
* Interpreted positive, negative, and near zero deviations
* Squared the deviations and explained why squaring removes negative signs and prevents values from cancelling out
* Summed the squared deviations
* Derived variance and standard deviation manually, then verified the result using `np.std()`
* Key takeaway: standard deviation reveals whether a class is evenly prepared or split between strong and struggling students, something the mean alone cannot show

## Exercise 3: Trigonometric Series and Convergence

* Converted an angle to radians using `np.radians()`
* Generated a sequence of terms using `np.arange()`
* Calculated sin(theta) using `np.sin()`
* Built a series of the form sin(theta) divided by k
* Summed the series at 100, 1000, and 10000 terms
* Key takeaway: the sum kept growing rather than settling, because every term is positive, this links to the harmonic series and its known divergence, and shows the difference between a sum that grows slowly and one that actually converges

## Bonus Challenge: Solar Panel Output Analysis

* Framed as an independent applied problem, Weekly Energy Yield
* Recorded 10 days of solar panel output as a NumPy array
* Calculated total and mean output
* Measured spread using standard deviation to judge output consistency
* Modeled a proposed 12% efficiency upgrade using vectorized multiplication
* Calculated the projected gain in output
* Key takeaway: low standard deviation indicated steady daily performance, and the 12% upgrade translated into a proportionate, low risk projected gain

## Concepts Demonstrated

* Array creation and inspection, shape, size, indexing
* Vectorized arithmetic across arrays
* Aggregation functions, sum and mean
* Manual derivation of variance and standard deviation, verified against NumPy's built in function
* Sequence generation with `np.arange()`
* Trigonometric functions and radian conversion
* Series summation and convergence reasoning
* Translating numerical output into a short, decision oriented interpretation

## Why This Matters

* Summarizing a series of values, measuring spread, modeling a percentage change, and judging whether a result actually stabilizes are steps that recur directly in return and volatility calculations, risk measurement, and time series work
* This notebook is a fundamentals checkpoint, not a finished analytical project

## Tools Used

* Python 3.10
* NumPy
* Jupyter Notebook

## Author

Wīsdøm, Mathematics undergraduate working toward a career in quantitative analysis.
