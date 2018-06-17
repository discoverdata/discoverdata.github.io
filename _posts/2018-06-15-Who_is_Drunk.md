---
title: "Exploratory data science project"
date: 2018-06-15
tags: [data science, R, Ames drink project]
header:
	image: "images/Amesdrunk"
excerpt: "Data Science project"
mathjax: true
---

# H1 heading 

## H2 heading

### H3 heading

Basic text
for *italics*

for **bold**

What about a [link](https://duckduckgo.com)

Here is a bulleted list:
* First
* Second
+ Thrid
- Fourth

here is a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
	import numpy as np
	def test_fun(x,y):
		sum = np.sum(x,y)
		return sum
```
Perl Code block:
```perl
	sub add ($x,$y){
	$sum = $x + $y;
	return $sum;
	}
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_text_file.csv")
head(df)
```

here is some inline code `x+y`

Here is an image:
<img src={{ site.url }}{{ site.baseurl }}/images/aboutme.jpg alt="about me">

Here is some math:

$$z = $$x + $$y 
