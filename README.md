# Are Avocado Prices a Good Indicator of Gentrification

A data analytics project attempting to correlate the gentrification of Atlanta, GA with avocado prices. The project contains five csv files, four Excel files, and one Jupyter notebook. The Jupyter notebook takes the csv files, cleans and merges them, then exports them as an Excel file to be used for visulaization in Tableau. The graphs on the Tableau dashboard show that in the same year the price of avocados peaked (2017) the city of Atlanta saw a slight decline in marginalized demographics. While this could just be a coincidence, more data will need to be implemented in order to draw a solid conclusion.


### Instructions:
1. Create a virtual environment with which to run the Jupyter Notebook.
    - Open a new terminal in your IDE, be sure it's a powershell terminal.
    - Run the script `python -m venv venvname`. This will create the virtual environment.
    - Activate the virtual environment by running the script `venvname\Script\Activate.ps1`.
2. Refer to **requirements.txt**.
3. Ensure modules are installed and Python is updated to at least version 3.9.13.
4. Open and run **avocado_gentrification.ipynb**. This will create four Excel files named **atlanta-census.xlsx**, **avo_yearly_avg.xlsx**, **avocado_years.xlsx**, and **piv_atlanta-census.xlsx**.
5. Refer to my [Tableau dashboard](https://public.tableau.com/views/AvocadosandGentrification/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) for visualized data.


### Features:
1. Read in data two or more csv files.
2. Clean data and perform a pandas merge with two or more datasets.
3. Make a Tableau dashboard to display data.
4. Utilize a virtual enviroment.