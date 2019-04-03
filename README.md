# the-hindu-archive-scraper
Python script to scrape The Hindu Print archive from http://www.thehindu.com/archive/

- Install the requirements using command:
  ```
    pip install -r requirement.txt
  ```
- Run the script:
  ```
    python script.py
  ```
- Parse articles using links
  Store links in links.txt
  ```
    python script2.py
  ```
  The script will write to stdout for each link in the following format: title|location|time|body
