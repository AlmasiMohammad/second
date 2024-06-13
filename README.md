# second
Answer to questions

As discussed before, these for questions have little bit of issues to be solved. Which is describe below:

Exercise 1:
Problem:
- The `id_to_fruit' function used a `set' to find the fruit names, but the `set' did not preserve the order of the elements, so the order of the fruits was different every time the function was run, and the indices could not be assigned correctly.
solution:
- We used ``list'' instead of ``set'' to preserve the order of the elements and to be able to access the elements correctly.

Exercise 2:
Problem:
- The `swap' function, which had the task of moving the coordinates of `x' and `y', did not move the coordinates correctly because the values ​​of the coordinates were not moved properly.
solution:
- Using a more suitable method for moving coordinates using `numpy' and moving columns was done correctly.

Exercise 3:
Problem:
- The ``precision-recall'' chart was not displayed correctly because the ``precision'' and ``recall'' values ​​were incorrectly placed on the ``x'' and ``y'' axes.
solution:
- Replacing the x and y axes with each other so that the precision and recall values ​​are displayed correctly.

Exercise 4:
Problem:
- In the `train_gan` function, the number of real and generated samples were not equal, and this caused a size error in `loss' calculations and updates.
solution:
- Use `current_batch_size' to ensure consistency of sizes at each stage and ensure that the number of actual and generated samples are equal.
