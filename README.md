# FAU_Airlines 1.4
## **How to install:**

**1) Get the Repository URL:**
Look for the "Clone or download" button on the right side of the repository page. Click on it, and you'll see a URL. Make sure it says "HTTPS" if you want to clone using HTTPS.

**2) Open Terminal or Command Prompt:**
Open your terminal or command prompt on your local machine. Navigate to the directory where you want to clone the repository.

**3) Use git clone Command:**
Type the following command, replacing <repository-url> with the URL you copied earlier:

```bash
git clone <repository-url>
```

**4) Press Enter:**
Press Enter, and Git will download the repository to your local machine. This may take some time, depending on the size of the repository and your internet connection.

## **File Path Adjustment:**
Before running the code, make sure to update the file path in the script to match the location of the CSV file on your local machine. Locate the following line in the code:
```python
file_path = '../../Files/fau_airlines_shifts.csv'
```
Replace '../../Files/fau_airlines_shifts.csv' with the correct path to the CSV file on your system.

## **Libraries Used:**
This project utilizes the following Python libraries:

1) Pandas: A powerful data manipulation and analysis library.
2) PuLP: A Linear Programming (LP) modeling tool for optimization problems.

## **Libraries Installation:**
Ensure you have the necessary libraries installed. You can install them using the following commands:
```bash
pip install pandas
pip install pulp
```
