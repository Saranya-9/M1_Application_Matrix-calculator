# M1_Application_Matrix-calculator
## Badges
[![C/C++ CI - Build Status](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/c-cpp.yml)
[![Code Quality - Static Code - Cppcheck](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/cppcheck.yml)
[![Unit Testing - Unity](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/unity.yml/badge.svg)](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/unity.yml)
[![Valgrind](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/Valgrind.yml/badge.svg)](https://github.com/Saranya-9/M1_Application_Matrix-calculator/actions/workflows/Valgrind.yml)

## Challenges Faced and How Was It Overcome

| No. | Challenge | Solution
|-----|-----------|--------
|1. | Dynamic memory allocation of 2D arrays created segmentation faults| running the code in GDB helped find the line where the program crashes
|2. | Program crashes | Writing clean code with allocating and deallocating memory at all functions as per requirement|
|3. | Logical errors faced while designing matrix operations| Referred some articles to revise matrix basics and operations on 2D arrays
|4. | Unit testing on dynamic 2D array outputs| Created enumerated variables to be returned by those functions if the specified operation executes successfully
