# Loan Qualifier App / Week 2 Challenge

This is a loan qualifier application. It asks for credit score and loan Size, and calculates debt-to-income ratio and loan-to-value ratio. Using these values the application matches the user with the loans that they qualify for and optionally saves them to a .csv file. This allows users to quickly and easily determine which loans they qualify for. 
    

---

## Technologies

This application is written in the python language. It uses the "sys", "csv", and "pathlib" modules along with the "fire" and "questionary" libraries. It has been developed and tested on MacOS

---
## Instillation
Before running the application install the following:

```python
pip install fire
pip install questionary
```
---
## Usage

When run, the application will first ask the user to enter a file path to a .csv file containing the rate-sheet by asking:
```Enter a file path to a rate-sheet (.csv```

It will then ask users:
```
What's your credit score?
What's your current amount of monthly debt?
What's your total monthly income?
What's your desired loan aount?
What's your home loan value?
```

The app will then display:
```
The monthly debt to income ratio is ...
The loan to value ratio is ...
Found ... qualifying loans
```

If the user qualifies for any loans the app with then ask:
```
Would you like to ave the loans that you qualify for to a CSV file? (Y/N)
```

If prompted "Y" the application will then ask :
```
Enter a file path to save the qualifying loans (.csv):
```

---

## Contributors

This application was developed by Jake Wheeler. I can be contacted at jpwheeler93@gmail.com

---

## License

MIT
