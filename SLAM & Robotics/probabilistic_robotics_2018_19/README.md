# Probabilistic Robotics 2018/19

Maintainers:
 - [Giorgio Grisetti](https://sites.google.com/dis.uniroma1.it/grisetti)
 - [Bartolomeo Della Corte](http://www.dis.uniroma1.it/~dellacorte/)
 - [Dominik Schlegel](https://sites.google.com/dis.uniroma1.it/schlegel)

Contents: <br/>
Teaching material for the [Probabilistic Robotics course](https://sites.google.com/dis.uniroma1.it/probabilistic-robotics) of the academic year 2018/2019

Supported environments: <br/>
Ubuntu 16.04 LTS

## What's where?
| Folder       | Description                                                                             |
| :----------- | :-------------------------------------------------------------------------------------- |
| literature   | Additional reading material related to the coursework                                   |
| applications | Octave/C++ example programs discussed in the course                                     |
| slides       | Lecture slides in PDF format                                                            |

## Want to have all the files on your computer?

Install [git](https://git-scm.com/):

    sudo apt-get install git
  
Clone (download) this repository somewhere on your computer:

    git clone https://gitlab.com/grisetti/probabilistic_robotics_2018_19
  
Later, as new material is added - one can conveniently update the local copy:

    cd probabilistic_robotics_2018_19
    git pull

## Application guide
### Requirements
Install [GNU Octave](https://www.gnu.org/software/octave/) or [MATLAB](https://mathworks.com/products/matlab.html) on your machine. <br/>

`Octave` can be installed by simply entering:

    sudo apt-get install octave
    
If you want to run the `Octave` examples on a Windows machine make sure to copy all files from
[visualization](https://gitlab.com/grisetti/probabilistic_robotics_2017_18/tree/master/applications/octave/tools/visualization) and
[utilities](https://gitlab.com/grisetti/probabilistic_robotics_2017_18/tree/master/applications/octave/tools/utilities)

### Optional Requirements
Install ROS by following the instructions for <br/>

  - [Ubuntu 16.04](http://wiki.ros.org/kinetic/Installation/Ubuntu) 

In both cases, install `ros-<VERSION>-desktop-full`

### Applications

 - [grid_orazio](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/04_grid_orazio) (Octave)
 - [ekf_localization](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/08_ekf_localization) (Octave)
 - [ekf_localization (bearing only)](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/09_ekf_localization_bearing_only) (Octave)
 - [ekf_slam](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/10_ekf_slam) (Octave)
 - [ekf_slam (unknown associations)](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/12_ekf_slam_unknown_association) (Octave)
 - [ukf_localization (known associations)](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/14_ukf_localization) (Octave)
 - [particle_localization (known associations)](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/16_particle_localization) (Octave)
 - [distance_map](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/cpp/17a_distance_map) (C++)
 - [kd_tree](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/cpp/17a_kd_tree) (C++)
 - [autodiff](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/cpp/17b_autodiff) (C++)
 - [ICP 2d](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/18_alignment_point_to_point_2d) (Octave)
 - [odometry_calibration](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/19_odometry_calibration) (Octave)
 - [ICP 3d](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/20_alignment_point_to_point_3d) (Octave)
 - [ICP 3d w/ Linear relaxation](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/octave/20b_alignment_point_to_point_3d_linear_relaxation) (Octave)
 - [Projective ICP](https://gitlab.com/grisetti/probabilistic_robotics_2018_19/tree/master/applications/cpp/24_projective_icp) (C++)

## Robotic news
[IEEE spectrum](https://spectrum.ieee.org/robotics) <br/>
[arXiv public library](https://arxiv.org/list/cs.RO/recent) <br/>
