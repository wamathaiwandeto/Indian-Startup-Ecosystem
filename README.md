# INDIA START-UP FUNDING ANALYSIS (2018 to 2021)  
This analysis offers a comprehensive look into the Indian startup landscape from 2018 to 2021. Focused on key trends, funding patterns, and investor involvement

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Installation
To run this notebook, you will need the following software and libraries:
#### Software:
- VScode or Jupyter Notebook
- Python 3
- Git and Github
- Microsoft Excel (for data cleaning)
#### Libraries (install using pip or conda):
- pyodbc
- dotenv
- pandas
- pandas_summary
- numpy
- squarify
- matplotlib
- seaborn
- scipy

## Usage
#### Key Focus Areas:  
- Trend Identification: Uncovering sectors experiencing significant growth and understanding funding distribution.  
- Funding Patterns: Analyzing how industry, rounds, and activities attract investments.  
- Diversification of startups: Analyzing the industry diversification in india
#### Project Goals:  
- Data Preparation: Ensuring a clean dataset for analysis by handling missing values and standardizing data types.  
- EDA Insights: Gaining valuable insights through exploratory data analysis, visualizing trends and funding distributions.
- Effective Communication: Creating clear visualizations and reports to communicate findings to stakeholders.
- Recommendations: Providing actionable strategies for startups, investors, and policymakers based on identified trends.  
#### Hypothesis Testing:  
- Null Hypothesis (H0): Funding is not influenced by the company's industry.  
- Alternate Hypothesis (H1): Funding is influenced by the company's industry.   

## Configuration
All four datasets for this were imported from excel. i.e
df_2018 = pd.read_excel("funding18.xlsx")   
df_2019 = pd.read_excel("funding19.xlsx")  
df_2020 = pd.read_excel("funding20.xlsx")  
df_2021 = pd.read_excel("funding21.xlsx")  

To get this datasets omline: Please [kaggle link](https://www.kaggle.com/datasets/omkargowda/indian-startups-funding-data?resource=download)
 
## Contributing
Welcome to the Indian Startup Funding Ecosystem project! I appreciate your interest in contributing to the project and helping me improve this analysis and insights.
#### Types of Contributions
I welcome contributions in the following areas:  
- Bug fixes
- Feature enhancements
- Data analysis improvements
- Documentation updates
- Code optimization
- Testing and validation
- Getting Started  
To get started with contributing, follow these steps:   
1. Fork the repository to your GitHub account.
2. Clone the forked repository to your local machine.
 on bash , Copy this code git clone https://github.com/wamathaiwandeto/Indian-Startup-Ecosystem.git
3. Set up your development environment. You will need Python 3 and the necessary libraries as mentioned in the "Installation" section of the README file.
4. Create a new branch for your contribution. Copy code - git checkout -b feature/new-feature
5. Make your changes and ensure that the code passes all tests and follows the coding guidelines. 
6. Commit your changes with clear and descriptive commit messages. Copy code: git commit -m "Add new feature:description of changes"
7. Push your branch to your forked repository. Copy code 'git push origin feature/new-feature'
8. Submit a pull request (PR) to the main repository. Provide a detailed description of your changes and why they are beneficial.
#### Coding Guidelines
Please adhere to the following coding guidelines:  
- Follow PEP 8 style guide for Python code.
- Use meaningful variable names and comments for better readability.
- Write clear and concise documentation for new features or changes.
#### Code Review
All contributions will undergo code review before merging. Reviewers will provide feedback and suggestions for improvement.
#### Issue Tracking
Check the issue tracker for open issues or create a new issue to discuss your proposed changes before starting work.
#### Acknowledgment
I appreciate all contributions and will acknowledge contributors in the project's README file and release notes.  
Thank you for contributing to the Indian Startup Funding Ecosystem project!
## License

This project is licensed under the [MIT License](https://github.com/wamathaiwandeto/Indian-Startup-Ecosystem/tree/main?tab=MIT-1-ov-file).
