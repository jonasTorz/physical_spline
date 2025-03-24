# physical_spline
Library to fit a 2D trajectory of a vehicle. Detailed explanation in the paper "Physical spline for denoising object trajectory data by combining splines, ML feature regression and model knowledge"

You can initialise the spline designer, spline designer 2D or a heading spline designer. Add different measurements of position, velocities, acceleration and heading. You can also add different types of regularization in order to prefer solutions with lower accelerations, lower acceleration changes and so on. After adding everything you can call get spline to get callable functions. 

Check out the example_notebook.ipynb
