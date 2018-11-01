# BOW 2018 hackaton workshop examples

## Turism indicators example (Highcharts)

1. Download data from [http://opencaribbean.org/dataset/belize-tourism-data](http://opencaribbean.org/dataset/belize-tourism-data)
    + [Accommodation Sector Indicators (XLSX)](http://www.opencaribbean.org/dataset/5a47d16a-930e-4200-aa09-530567d50a9e/resource/2a0cff37-c9d8-4a03-ab4a-2082d0993826/download/accommodation-sector-indicators.xlsx)
2. Convert XLSX to CSV (look for sheet of "average daily prices")
    + Create new sheet
    + Copy and "paste special" the table in the new sheet, transposing rows to columns
    + Change names ("Area" to "year", "Total" to "Belize Total Average")
    + Save as CSV file
3. Upload CSV to Github
    + "Upload files" in the repository
    + Drag and drop
4. Create an HTML file with a [Highcharts Basic Line chart](https://www.highcharts.com/demo/line-basic) in it, using that CSV file
    + Create an empty HTML file
    + Copy/Paste the 3 parts of "Basic Line" chart demo (click in "EDIT IN CODEOPEN"): HTML, CSS (inside a "style" tag) and JS (inside a "script" tag).
    + Change the chart to use your uploaded CSV file, title, subtitle, etc. **(see the [final example in this repository](https://github.com/abenassi/workshop-html-bow2018/blob/master/highcharts.html))**
5. Activate "Github Pages" in your repo
    + "Settings" > "Github Pages" > Activate on "master branch"

See how the highcharts.html looks like: https://abenassi.github.io/workshop-html-bow2018/highcharts.html

## Turism map example (Datawrapper)

1. Download data from http://opencaribbean.org/dataset/belize-tourism-data (http://www.opencaribbean.org/dataset/5a47d16a-930e-4200-aa09-530567d50a9e/resource/2f684ed8-4e6f-4baf-8a1a-425a8b241f8c/download/belize-sites-and-attractions-listing.csv) 
2. Create e New map in Datawrapper (https://datawrapper.de/)
3. Go to "Dashboard" section
4. Click on create a "New map".
5. Choose "Symbol map"
6. Follow the next steps with the tool.
7. See tutorial: http://academy.datawrapper.de
8. See video tutorial: https://www.youtube.com/watch?v=Ni8PmmC2IWs
9. See result: https://datawrapper.dwcdn.net/fkNSS/1/

