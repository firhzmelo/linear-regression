# Full Linear Regression

On my previous repo of [simple-linear-regression](https://github.com/firhzmelo/simple-linear-regression), i implemented from scratch linear regression with only 1 parameter. This time i will try to apply that algorithm on a real dataset, preprocess the data and visualize it. I used the same resources from the last repo of linear regression to build this.

On my first day of building the projecti couldn't make it work, since the weights ended up with inf or -inf, then i decided to include the Scikit Learn StandardScaler, this helped a lot, since i was working with really big numbers and the dot products had really high values

On the second day i tried to reverse the effect of the StandardScaler, and this was a really annoying task, since i had to re do the scaler and then suddenly i had problems with my fit method due to wrong shape in the dot propuct. At the end i made some modifications and optimizations avoiding an extra for loop.

It was a lot of fun, but i had really stressful moments too.
