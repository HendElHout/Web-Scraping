Approach:
script is designed to scrape various types of data from a web page and save it in structured formats
1-Text Data Extraction: Extracts headings, paragraphs, and list items from the HTML.  and save data to CSV file
2-Table Data Extraction:Extracts rows containing product name, price, and stock status and also save the data to CSV file
3-Product Information Extraction:Extracts book titles, prices, stock availability, and button text from styled containers.
   saved this data in 2 files CSV and JSON file
4-Form Details Extraction:Extracts input field names, types, and default values from forms on the page.
5-Links and Multimedia Extraction:Extracts video sources
6-Featured Products Extraction:Extracts product details such as name, ID, hidden price, and available colors from a special section

Tools Used:
-requests:fetch the HTML content of the webpage
-BeautifulSoup:parse through the HTML structure to extract data
-csv:save tabular data (headings, paragraphs, list items, and table data) into CSV files
-json:save structured data to json file
-re (Regular Expressions):clean the text by removing unwanted characters and symbols

Challenges Faced:
-Identifying Correct HTML Elements
-Dynamic Content
-Error Handling
-Data Cleaning
-Saved to multiple formats
  
