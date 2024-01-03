# Reverb


## CMake

Install [CMake](https://cmake.org/).
In order to generate your project with CMake, follow these steps:

```
cd /path/to/Reverb
cmake -B build -G XCode     # to generate and build with a XCode project
sudo cmake --build build
```
or
```
cd /path/to/Reverb
cmake -B build             # to generate with the default generator
sudo cmake --build build
```

### First Aid Troubleshooting

If you encounter issues while building the CMake project after already built it before, please try to delete the build folder before a new cmake command:
```
cd /path/to/Reverb
sudo rm -rf build 
```