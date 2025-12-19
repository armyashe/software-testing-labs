
# Software Testing Labs

This repository contains assignments for the **Software Testing** course.

All submissions are organized **by week (lab)** and include:

* Implementation code
* Test scripts
* Requirement documentation

---

##  Repository Structure

Each lab follows the structure below:

* `labN/code/` – C++ source code
* `labN/input/` – Test case input files (`.inp`)
* `labN/output/` – Program outputs (`.txt`)
* `labN/docs/` – Problem statements and reports
* `labN/test.ipynb` – Notebook to compile, run, and validate tests

---

##  Testing

* Test inputs are stored as `.inp` files inside the `input/` directory
* Programs are compiled from the `code/` directory and executed with redirected input
* Outputs are saved in the `output/` directory and compared against **expected results**
* Automated validation is implemented in `test.ipynb`

---

##  Evidence of Development Process (Daily Work Tracking)

The complete **development process by day**, including:

* Draft files
* Intermediate versions
* Screenshots
* Notes and progress tracking

is documented in the following Google Drive folder:

🔗 **Google Drive – Working Process Evidence**
[https://drive.google.com/drive/folders/112atteEiHg65SNAQ5oyFvINqBCT8lEmW?usp=sharing](https://drive.google.com/drive/folders/112atteEiHg65SNAQ5oyFvINqBCT8lEmW?usp=sharing)

This link is provided to **demonstrate the development process**, not only the final submission.

---

##  Notes

* Each lab corresponds to a **specific Software Testing topic**
* The repository supports:

  * Website Fast Food Ordering testing:
    [https://fast-food-app-nu.vercel.app/](https://fast-food-app-nu.vercel.app/)
  * Test planning
  * Test case design
  * Test execution and validation
  * Expected vs Actual result comparison
* The structure is designed for **easy review, grading, and future extension**

---

## How to Run

### 1. Clone the repository and navigate to a lab folder

```bash
git clone https://github.com/<your-username>/software-testing-labs.git
cd software-testing-labs/lab1
```

---

### 2. Set up the environment

**Install g++**

```bash
sudo apt update
sudo apt install g++
```

**Install Python (>= 3.8) and Jupyter Notebook**

```bash
pip install notebook
```

---

### 3. Run the assignment

Open the test notebook:

```bash
jupyter notebook test.ipynb
```

Inside the notebook, the test workflow will:

* Compile the C++ program from `code/practice1.cpp`
* Read inputs from `input/testcasePrac1.inp`
* Execute the program and capture outputs
* Compare results with expected outputs
* Write logs into `output/outputPrac1.txt`

---

### 4. Example output in the notebook

```text
Test 1: Output=Infinite solutions    Expected=Infinite solutions
Test 2: Output=No solution           Expected=No solution
Test 3: Output=No solution           Expected=No solution
...
```

---

### 5. Check results

The complete results are stored in:

```text
lab1/output/outputPrac1.txt
```

---


