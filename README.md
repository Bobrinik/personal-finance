## Requirements:
- [Familiarity with Jupiter Notebook](https://realpython.com/jupyter-notebook-introduction/)
- Have a google account

## Instructions
- Current notebook will work out of the box with exported from RBC csv (unless they have changed columns since the making of this notebook). To download the csv file log into your RBC account and click on credit or debit account links. Once in there, you'll have an option to download operations. It's located right on top of the transactions table. Click on the link and select an option that separates values with commas (not sure for exact phrasing of this one) after that click on continue. You should see a file that can be saved on your computer the file name ends with `.csv`.
- Once the file is dowloaded onto your computer, you can upload it into Google Drive. Create a folder called `rbc_bank` and place your `.csv` file into there.
- Then open [this notebook](https://github.com/Bobrinik/personal-finance/blob/master/Finances.ipynb) in Google Collab and modify the following line `pd.read_csv('My Drive/rbc_bank/your_rbc_file_name.csv'`. You should be set.
