# Software Testing Labs

Repository for assignments of the **Software Testing** course.

All submissions are organized by week and include:

- Implementation code
- Test scripts
- Documentaion of requirements

## Repository Structure

- `labN/code/` : C++ source code
- `labN/input/` : Test case files (.inp)
- `labN/output/` : Program outputs (.txt)
- `labN/docs/` : Problem statements and reports
- `labN/test.ipynb` : Notebook to compile, run, and validate

## Testing

* Test inputs are stored as `.inp` files inside `input/`.
* Programs are compiled from `code/` and executed with redirected input.
* Outputs are saved in `output/` and compared against the  **expected results** .
* Automated validation is implemented in [`test.ipynb`]().

### How to Run:

#### 1. Clone the repository and navigate to the lab folder

```
git clone https://github.com/`<your-username>`/software-testing-labs.git
cd software-testing-labs/lab1

```

#### 2. Set up the environment

* Install **g++** (if not already installed):

  ```
  sudo apt update && sudo apt install g++

  ```
* Install Python (>= 3.8) and Jupyter Notebook:

  ```
  pip install notebook

  ```

#### 3. Run the assignment

Open the test notebook:

```
jupyter notebook test.ipynb

```

Inside the notebook, the test workflow will:

* Compile the C++ program from `code/practice1.cpp`.
* Read inputs from `input/testcasePrac1.inp`.
* Execute the program and capture the outputs.
* Compare results with the expected outputs.
* Write logs into `output/outputPrac1.txt`.

Example output in the notebook:

```
Test 1: Output=Infinite solutions                         Expected=Infinite solutions
Test 2: Output=No solution                                Expected=No solution
Test 3: Output=No solution                                Expected=No solution
...

```

#### 4. Check results

The complete results are stored in:

```
lab1/output/outputPrac1.txt

```
