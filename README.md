# AWS SageMaker Notebook – CSV Data Analysis and Visualization

## Overview

This project demonstrates how to perform cloud-based data analysis using **Amazon Web Services (AWS)**. The employee dataset is stored in **Amazon S3**, accessed through an **Amazon SageMaker Jupyter Notebook**, analyzed using **Pandas**, and visualized using **Matplotlib**.

The project illustrates the complete workflow of creating cloud resources, importing datasets, performing exploratory data analysis, and generating meaningful visualizations.

---

## Objective

- Create an Amazon S3 bucket.
- Upload a CSV dataset.
- Create and configure an Amazon SageMaker Notebook Instance.
- Analyze the dataset using Python.
- Generate graphical visualizations using Matplotlib.

---

## AWS Services Used

- Amazon S3
- Amazon SageMaker AI
- AWS IAM
- Amazon CloudWatch (Notebook Monitoring)

---

## Python Libraries Used

- Pandas
- NumPy
- Matplotlib

---

## Dataset

The project uses an Employee Dataset containing the following attributes:

| Column | Description |
|---------|-------------|
| EmployeeID | Unique employee identifier |
| Name | Employee name |
| Department | Department of the employee |
| Salary | Employee salary |
| Experience | Years of experience |

---

## Project Workflow

1. Sign in to the AWS Management Console.
2. Create an Amazon S3 bucket.
3. Upload the employee_data.csv dataset.
4. Create an Amazon SageMaker Notebook Instance.
5. Configure an IAM role with S3 access.
6. Launch Jupyter Notebook.
7. Import the required Python libraries.
8. Load the dataset using Pandas.
9. Perform exploratory data analysis.
10. Generate visualizations:
    - Salary Comparison Bar Chart
    - Department Distribution Pie Chart
    - Employee Experience Line Chart

---

## Files Included

- `employee_data_analysis.ipynb` – SageMaker Jupyter Notebook containing the implementation.
- `employee_data.csv` – Employee dataset used for analysis.
- `Project_Report.pdf` – Complete project report with implementation steps and screenshots.
- `AWS_SageMaker_Project_Screenshots.zip` – Screenshots captured during project execution.
- Other PNG files – Individual screenshots showing AWS configuration, notebook setup, and outputs.

---

## Visualizations Generated

### Salary Comparison

Compares employee salaries using a bar chart.

### Department Distribution

Shows the percentage of employees in each department using a pie chart.

### Employee Experience

Displays employee experience using a line chart.

---

## Learning Outcomes

Through this project, the following concepts were learned:

- Working with Amazon S3 for cloud storage.
- Creating and managing Amazon SageMaker Notebook Instances.
- Configuring IAM roles for secure resource access.
- Importing CSV datasets using Pandas.
- Performing basic data analysis.
- Creating professional data visualizations using Matplotlib.

---

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

Install dependencies using:

```bash
pip install pandas numpy matplotlib
```

---

## Output

The project successfully loads the employee dataset, performs statistical analysis, and generates three visualizations to understand employee salary distribution, department-wise employee distribution, and employee experience.

---

## Author

**D Varsha**

B.E. Computer Science and Engineering (Artificial Intelligence & Machine Learning)

East Point College of Engineering and Technology

---

## License

This project is intended for educational and learning purposes.
