[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) [![Generic badge](https://img.shields.io/badge/fun-project-red.svg)](https://shields.io/) [![Maintenance](https://img.shields.io/badge/Maintained%3F-no-yellow.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) ![Terminal](https://badgen.net/badge/icon/terminal?icon=terminal&label)

## Scrapper
Python automation script to see rank, marks, name etc. of all the candidates who gave PUMEET exam
- [PUMEET](https://pumeet.puchd.ac.in/) is an entrance examination for migration/department change across [Panjab University](https://puchd.ac.in) colleges
  


## How to use this?
Just run the script & see the output in the console/terminal

### Pre-requisites
1. Selenium `pip install selenium`
2. Webdriver for your browser (Using any `Chromium` based browser is recommended for this):
    - For Chrome, install [chromedriver](https://chromedriver.chromium.org/downloads)
    - For Firefox, install [geckowebdriver](https://github.com/mozilla/geckodriver/releases)

3. Shortcut: if the webdriver isn't installed in the system path, you can just provide its location as:
```python
    driver = webdriver.Chrome("/path/to/webdriver")
    # OR
    driver = webdriver.Firefox("/path/to/webdriver")
```
4. (If you are on Windows, make sure to put `.exe` in the path, i.e., `driver = webdriver.Chrome("/path/to/webdriver.exe")`

5. (Optional) Print to the console or use Pandas library to import this to a python list or whatever to sort it according to the rank.
(Sorted version in `./assets`)


