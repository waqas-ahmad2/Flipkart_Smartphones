# Smartphone Scraper

This Python script scrapes smartphone data from Flipkart and stores it in a Pandas DataFrame. It extracts information such as original price, discounted price, image URL, description, total ratings, total reviews, and average rating for each smartphone.

## Installation

1. Clone the repository:

    ```git
     git clone https://github.com/{'your-username'}/smartphone-scraper.git
2. Install the required dependencies:
  pip install requests pandas numpy beautifulsoup4

  ## Usage

   1. Open the script `smartphone_scraper.py` in your preferred Python editor or IDE.

   2. Configure the desired number of pages to scrape by modifying the range in the `for` loop:
    
      ```python
      for page in range(1, 218):
          # ...
    
3. Run the script:
    ```shell
    smartphone_scraper.py
  
4. The script will scrape the specified number of pages and store the data in a Pandas DataFrame.

5. Optionally, you can perform further operations on the final DataFrame to analyze or manipulate the data as needed.



## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

## License
This project is licensed under the  GNU LESSER GENERAL PUBLIC LICENSE.
You can customize the content as per your requirements and include any additional sections or details. Also, make sure to replace `your-username` in the installation instructions with your actual GitHub username.

