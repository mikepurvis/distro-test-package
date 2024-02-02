# Distro Test Package

The branches in this repo are meant to exercise snapshot freezing, and in
particular the SES-4704 functionality that allows a .ros-repo.yaml config
file to be placed in the root of the repo that limits feature branches to
being eligible only for freezing within a particular distro.

- **ros-feature** - should only be selected for the `ros` distro
- **ros2-feature** - should only be selected for the `ros2` distro
- **generic-feature** - should be selected always when matching
