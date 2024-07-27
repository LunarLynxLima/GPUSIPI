# CUDA at Scale Independent Project

## Description
This project demonstrates the use of CUDA to process data in parallel on the GPU. The project includes a simple example where an array of integers is doubled using a CUDA kernel.

## File Structure
- `main.cpp`: The main C++ source file containing the CUDA kernel and host code.
- `Makefile`: Makefile to compile the project.
- `run.sh`: Script to run the project with command-line arguments.
- `LICENSE`: License file.
- `.gitignore`: Git ignore file.

## How to Build and Run

### Prerequisites
- CUDA Toolkit
- GCC

### Build
```sh
make

./run.sh --input data/input.txt --output results/output.txt --iterations 10
```

## Code Quality
The code follows the Google C++ Style Guide.


## License
This project is licensed under the MIT License - see the LICENSE file for details.


### Compilation and Execution

With all files in place, compile and execute the project using the provided `Makefile` and `run.sh` scripts. Ensure all paths and dependencies are correctly configured.

### Proof of Execution

Run the code with test data and provide screenshots or logs of the execution to demonstrate that the code runs successfully on the specified input data.

This should provide a complete structure and meet the project requirements as per the rubric. If you need further customization or have specific requirements, feel free to let me know!
