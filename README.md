# Loan Qualifier Application

Command line interface application that lets users determine which banks can provide a loan based on the user's input for credit score, debt, income and value of asset. The application uses a 'daily rate sheet' and outputs a file with qualifying loans. 
---

## Technologies

This project leverages python 3.9 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entrypoint.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs
---

## Installation Guide

Before running the application first install the following dependencies.

```python

pip install fire
pip install questionary 

```
---

## Usage

To use the loan qualifier application simply clone the repository and run the **app.py** with:

```python
python app.py
```

Upon launching the loan qualifier application you will be greeted with the following prompts.

![Loan Qualifier Prompts](Images/loan_qalifier.png)

---

## Contributors

Created and designed by Niels de Haan in colaboration with Columbia Fintech Bootcamp

---

## License

GNU GPLv3
