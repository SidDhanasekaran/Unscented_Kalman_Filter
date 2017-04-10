## Unscented Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

---

## Dependencies

* cmake >= v3.5
* make >= v4.1
* gcc/g++ >= v5.4

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./UnscentedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./UnscentedKF ../data/sample-laser-radar-measurement-data-1.txt output.txt`

## Code Style

Please stick to [Google's C++ style guide](https://google.github.io/styleguide/cppguide.html) as much as possible.

## Generating Additional Data

This is optional!

If you'd like to generate your own radar and lidar data, see the
[utilities repo](https://github.com/udacity/CarND-Mercedes-SF-Utilities) for
Matlab scripts that can generate additional data.


## Summary

This project is an implementation of an Unscented Kalman Filter in C++. The filter utilizes both laser and radar data inputs, as each has its own advantages. Laser data can accurately define an object's position in space. Radar data provides valuable speed data that can be used to track an object's velocity relative to the sensor. 


## Results (Terminal)

The following results for Root Mean Square Error (RMSE) Accuracy were produced for each set of data, respectively:

**sample-laser-radar-measurement-data-1.txt**

| Variable | RMSE |
|:--------:|:----:|
| px       | 0.082367  |
| py       | 0.0892043 |
| vx       | 0.605842  | 
| vy       | 0.588234  |

**sample-laser-radar-measurement-data-2.txt**

| Variable | RMSE |
|:--------:|:----:|
| px       | 0.195318 |
| py       | 0.188745 |
| vx       | 0.400681 | 
| vy       | 0.482468 |


