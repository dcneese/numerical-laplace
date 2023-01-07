# Visualizing Numerical Solvers of Laplace's Equation

This notebook was made for as the final project of a computational physics class, primarily as a pedagogical tool to help understand numerical differential equation solvers and Laplace's equation in E&M.

It had a few motives:
- I like making spatial visualizations of more abstract physics and mathematics concepts
- I think electrostatic potential fields suit themselves to this sort of visualization - especially with changing charge configurations
- Solving Laplace's equation by the method of relaxation also yields an interesting visualization - one that (a) can help show how the math updates the solution over time (i.e. how it "relaxes") and (b) looks really cool when animated

Throwing in a few different charge configurations and two different numerical solvers, I create some demos to show what the fields 'look' like and how the solvers find them from boundary conditions.

The `.ipynb` file is too large to display in github (32 MB - mostly due to one large animation), so I'll link a colab [here](https://drive.google.com/file/d/1WNQRlDJrTfTxqvc20iZcKVDdVsxaxuhV/view?usp=sharing) for convenient viewing.

As a (low resolution) taste, here's one of the final animations I produced, a potential field produced by successive-over-relaxation between two plates of charge:

![](https://github.com/dcneese/numerical-laplace/blob/main/sor_animation.gif)

This project is licensed under the MIT license.
