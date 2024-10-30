### Getting help on a function
---
- [help](#help)
- [example](#example)
---

  ## help
* Use ```help``` to display documenation of a function
```r
help(functionname)
```
* imagine you want help on mean function mean  use ```help``` or a short way ```?```
```
?mean
```
* Sometimes you just want a quick reminder of the arguments to a
function: What are they, and in what order do they occur? Use
the args function:
```r
args(mean)
```
## example 
* If you don't how function work you can request example
```
example(mean)
```
Output:
```r
mean> x <- c(0:10, 50)

mean> xm <- mean(x)

mean> c(xm, mean(x, trim = 0.10))
[1] 8.75 5.50
```
