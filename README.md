# Software Testing Labs

Repository for assignments of the **Software Testing** course.

All submissions are organized by week and include:

- Implementation code
- Test scripts
- Documentaion of requirements

## Repository Structure

- `labN/code/` : Source code and input/output files
- `labN/docs/` : Problem statements and reports

## Testing

* Test inputs are stored as `.inp` files.
* Expected outputs are compared against program results.
* Example inside [`test.ipynb`]().

### How to Run:

Example for **Lab 1 - Exercise e**:

* **Run via Terminal:**

```
cd lab1/code
g++ baie.cpp -o baie
./baie < baie_t1.inp > out.txt
cat out.txt
```

* **Run inside Jupyter Notebook**

  ```
  !g++ baie.cpp -o baie
  !./baie < baie_t1.inp > out.txt
  !echo "Expected: 3"
  !cat out.txt
  ```
