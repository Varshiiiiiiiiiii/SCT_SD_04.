# Web Scraping

**Problem Statement:** Create a program that extracts product information, such as names, prices, and ratings, from an online e-commerce website and stores the data in a structured format like a CSV file.

**Procedure:**
1. Import necessary libraries: csv, requests, BeautifulSoup, tkinter for GUI elements.
2. Define a function scrape_amazon_products to scrape product information from Amazon based on the provided name and minimum price.
3. Define a function save_to_csv to save the scraped product information into a CSV file.
4. Define a function get_user_input to prompt the user for the product name and minimum price through a GUI dialog box.
5. In the get_user_input function, create a hidden Tkinter window, prompt the user for the product name and minimum price using simpledialog.askstring.
6. Split the input string into the product name and minimum price, converting the latter to a float.
7. In the main block, call the get_user_input function to retrieve the product name and minimum price.
8. Call the scrape_amazon_products function with the retrieved product name and minimum price.
9. If products are found, save the scraped data to a CSV file using the save_to_csv function and display a success message using messagebox.showinfo.
10. If no products are found, display a message using messagebox.showinfo indicating that no products match the criteria.

**Technologies Used:**
1. Python
2. CSV (A module in Python)
3. Requests (A Python library )
4. BeautifulSoup (A Python library)
5. Tkinter (A standard GUI toolkit)

**Application:** The application is designed to provide users with a convenient way to browse and compare laptops available on the market, particularly focusing on mid-range to high-end models priced around ₹80,000. It aggregates information from various sources, including online retailers like Amazon, to present users with a comprehensive list of laptops along with their prices and ratings.

**Preview:**

Sample Input:

![image](https://github.com/SasankSami21/PRODIGY_SD_05/assets/112636647/13df8d2b-1abb-418b-b6a3-23d8d2be192f)

Sample Output:(image of .csv file)

![image](https://github.com/SasankSami21/PRODIGY_SD_05/assets/112636647/b40a5bd7-d20b-49bf-a049-68ab36c341a2)


