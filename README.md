# LearnChromeDriver
Learning about the chromedriver.exe


## 1. Download the [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) 

## 2. Copy the ChromeDriver to your Chrome's installation path   
### *Note:*    
  Typing the `chrome://version/` to the Chrome Address Bar to find your Chrome's installation path  
  The default installation path should be `C:\Program Files (x86)\Google\Chrome`  
  In other words, Copying the `chromedriver.exe`to the Path of `C:\Program Files (x86)\Google\Chrome\Application`

## 3. Copying the installation path of ChromeDriver to the System Environment Variables  
### *Note:*  
  Add the `C:\Program Files (x86)\Google\Chrome\Application\chromedriver.exe` to the System Path  

## 4. Simple test with `Selenium` in Pycharm

```Python
from selenium import webdriver

browser = webdriver.Chrome()
browser.get('http://www.baidu.com/') //Python
```
## 5. Jump to `Selenium` Part
* [Selenium with Python](http://selenium-python.readthedocs.io/index.html)
