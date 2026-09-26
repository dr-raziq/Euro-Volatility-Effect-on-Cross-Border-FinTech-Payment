The Effect of Euro Volatility on Cross-Border FinTech Payment

    MSc Financial Technology - Applied Research Project

    Author: Mohammad Raziq Mohammad Arshad Shaikh  
    Institute: Dublin Business School
    Supervisor: Dr. P.J Paul  
    Date: September 2026


Description

    This project analyses how Euro exchange rate fluctuations affect the final cost of cross-border payments on PayPal, Wise, and Revolut. It uses ECB exchange rates from 2015 to 2019 and multiple regression analysis.


Files

    •	`ecb_data.ipynb` - downloads ECB validation data.
    •	`data_filtration.ipynb` - filters EUR pairs.
    •	‘data_preparation.ipynb’ - cleans data and generate `cleaned_data_for_python.csv’
    •	`time_series_analysis.ipynb` - seasonal and day-of-week analysis.
    •	`multiple_regression_analysis.ipynb` - regression analysis.
    •	`cleaned_data_for_python.csv` - cleaned dataset used by the analysis notebooks.
    •	‘Platform Fees’ – have platform fees info in PDF format.
    •	`report.pdf` - final report.
    •	Other CSV, XLSX, TXT, and PDF files are outputs.


How to Run

    1. Clone GitHub repository
    2. Install Python.
    3. Install packages: ‘pip install -r requirements.txt’
    4. Open the notebooks in VS Code.
    5. Run the notebooks in this order:
            •	ecb_data.ipynb
            •	data_filtration.ipynb
            •	time_series_analysis.ipynb
            •	multiple_regression_analysis.ipynb
    6. Make sure to setup dataset’s path in each of notebooks accordingly. 


Structure

    Euro Volatility Effect on Cross-Border FinTech Payment
    |
    |_ 1_ECB data
    |	|_ 1_ecb_data.ipynb
    |	|_ 1_ecb_rates.csv
    |
    |_ 2_Filtered data
    |	|_ 2_data_filtration.ipynb
    |	|_ 2_filtered_eur_rates.csv
    |
    |_ 3_Processed data
    |	|_ 3_data_preparation.ipynb
    |	|_ 3_cleaned_data_for_python.csv
    |
    |_ multiple_regression_analysis.ipynb
    |
    |_ time_series_analysis.ipynb
    |
    |_ Platform fees
    |	|_ paypal.pdf
    |	|_ revolut.pdf
    |	|_ wise.pdf
    |
    |_ Platform Summary
    |	|_ Paypal_summary
    |	|	|_ paypal_EUR_GBP_summary.txt
    |	|	|_ paypal_EUR_JPY_summary.txt
    |	|	|_ paypal_EUR_USD_summary.txt
    |	|
    |	|_ Revolut_summary
    |	|	|_ revolut_EUR_GBP_summary.txt
    |	|	|_ revolut_EUR_JPY_summary.txt
    |	|	|_ revolut_EUR_USD_summary.txt
    |	|
    |	|_ Wise_summary
    |		|_ wise_EUR_GBP_summary.txt
    |		|_ wise_EUR_JPY_summary.txt
    |		|_ wise_EUR_USD_summary.txt
    |
    |_ Tables
    |	|_ best_worst_months.csv
    |	|_ day_of_week_analysis_table.csv
    |	|_ savings_estimate_table.csv
    |	|_ seasonal_analysis_table.csv
    |
    |_ Visuals
    |	|_day_of_week_effects.pdf
    |	|_ long_term_trends.pdf
    |	|_ Platform_cost_trends.pdf
    |	|_ seasonal_patterns.pdf
    |
    |_ Result
    |	|_ How_to_Save_Money_on_Cross_Border_Payments.txt
    |	|_ hypothesis_test_results.xlxs
    |	|_ regression_coefficients.xlxs
    |	|_ regression_diagnostics.pdf
    |
    |_ report.pdf
    |
    |_ requirements.txt
    |
    |_ README.md
    |
    |_ LICENSE


Note

    Please open all PDF files on your desktop, it will not work on VS code.
    For more information please check ‘report.pdf’


   

