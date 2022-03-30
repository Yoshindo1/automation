# automation

In "automation", the source code used in my business is partially modified and released.
This repository contains codes to help you proceed simple tasks that can be used in other industries.

# feature:
・ Aggregate_monthly_orders.py
By inputting the domestic zip code of the order matter data, it is aggregated at the granularity of each prefecture and visualized with a heat map on the Japanese map.
Since it uses an external API, it outputs prefecture and municipal data without being affected by fluctuations such as typo at manual input.
Aggregate data and visualization graphs also automatically generate XLSX format reports at the given destination.

・ Sample01_3month.xlsx
This is a sample of input data. If you want to change the name of the stored folder, revise the input_dir object that specifies the path in the source code.

#Requirement:
Data processing
* pandas
* regex
* requests


Graph drawing
* matplotlib
* japanmap

File export
* xlsxwriter
* openpyxl

#Usage
Running in Google Colaboratory is recommended, since it is not easily affected by the usage environment. Below, it is assumed that the corresponding notebook file has been uploaded on Google Drive.
1. Unzip the cloned repository and upload it to Google Drive.
2. Select the .ipynb file and select Google Colaboratory.
3. Select "Run cells" or "Run all cells" sequentially from the runtime tab.

#Author
* Yoshito Ishii
* mail: yoshindo.keyhole@gmail.com

#License
Copyleft by Yoshito
