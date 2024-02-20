# Overview

The objective of this project is to translate the Python code for implementing the two-dimensional histogram filter into C++. The task is to fill in the functions identified by TODO comments until the histogram filter functions as intended!

To verify the correctness of your implementation, you can compile tests.cpp and execute the output. You can accomplish this by running the following command from the command line.

## Project Files

There are only two files you need to worry about for this project: [helpers.cpp](./helpers.cpp) and [localizer.cpp](./localizer.cpp). Here's what each file included in the starter code is for:

You can mostly ignore any .h (header) files, although if you add additional functions to .cpp files you should also define them within the related header file! The maps folder just has data of the map data used in the project

- **tests.cpp** is just for testing - no need to touch it
- **debugging_helpers.cpp** is to help you debug; don't need to implement anything
- **helpers.cpp** - Implement `normalize()` and `blur()`
- **localizer.cpp** - Implement `initialize_beliefs()`, `sense()` and `move()`
- **simulate.cpp** - You can uncomment portions of this to further help you develop the project, but this is not needed just to pass. 

## How to execute

1 - Clone this repository

```bash
git clone https://github.com/Morsinaldo/ISDC-Translate-Python-Cpp.git
```

2 - Enter in the repository folder

```bash
cd SDC-Translate-Python-Cpp
```

3 - Compile the project

```bash
g++ localizer.cpp helpers.cpp debugging_helpers.cpp
```

4 - Execute

```bash
./a.out
```

To verify the correctness of your implementation, you can compile tests.cpp and execute the output. You can accomplish this by running the following command from the command line.

```bash
g++ tests.cpp
./a.out
```

## Project Rubric

1 - **Code works as expected**: Code passes the provided tests in tests.cpp

2 - **initialize_beliefs** works correctl: `initialize_beliefs` is implemented the right way.

3 - **sense works correctly**: `sense` is implemented the right way.

4 - **move** works correctly: `move` is implemented the right way.

## Referece

[Introduction to Self-Driving Cars NanoDegree](https://learn.udacity.com/nanodegrees/nd113)