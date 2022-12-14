# Fast SLAM
It is an implementation of the paper [FastSLAM: A Factored Solution to the Simultaneous Localization and Mapping Problem](http://robots.stanford.edu/papers/thrun.fastslam.pdf) by Sebastian Thrun, Wolfram Burgard and Dieter Fox. It is a particle filter based SLAM algorithm.

## Dependencies
* Python 3.6 or above
* Numpy
* Matplotlib

## Usage
```
python fast_slam.py
```
## Structure
* `fast_slam.py` - Main file
* `data` - Contains files representing the world definition and sensor readings used by the filter.

## Notes on the implementation
- Each particle uses a 2x2 EKF for every Landmark.
- EKF is implemented for the Correction step.
- There is an animation demonstration of robot motion and measurement updates.