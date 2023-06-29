# PrizePicks Web Scraper

You can find the webscraper inside the repo along with a test file. _*ppWebScraper*_ successfuly scrapes the PrizePicks website and neatly organizes all of the props for your selected sport in a CSV file for your convenience!

## Packages Needed

- Selenium
- Pandas
- ChromeDriver 
- undetected_chromedriver



If you wish to run this program, download the source files and edit it in your favorite IDE. You can also run it directly in terminal.

## Installation


```sh
pip install selenium
pip install pandas
```

Once you downloaded the file, you will have to edit the PATH directory for your ChromeDrive/WebDriver and change the sport to your liking as the default is NBA. Next, you can execute:

```sh
python ppWebScraper.py
```
The program should now run and print a portion of the results along with a CSV file. 

## v1.2
- Users were reporting issues with the program getting flagged by Cloudflare.
- Added undetected_chromedriver functionality to circumvent this issue.
- Added Ability to switch sports to scrape.
 

## License

MIT
