# Selenium-installation
Procedure to install selenium-python and driver configure
**Selenium Python** bindings provides a simple API to write functional/acceptance tests using Selenium WebDriver. Through Selenium Python API we can access all functionalities of Selenium WebDriver in an intuitive way.
Selenium Python bindings provide a convenient API to access Selenium WebDrivers like **Firefox**, **Ie**, **Chrome**, **Remote etc**. The current supported Python versions are 2.7, 3.5 and above.

## Downloading Python bindings for Selenium
We can download Python bindings for Selenium from the PyPI page for selenium package. However, a better approach would be to use pip to install the selenium package. Python 3.6 has pip available in the standard library. Using pip, you can install selenium like this:

```
pip install selenium
```

Selenium requires a driver to interface with the chosen browser. Firefox, for example, requires geckodriver, which needs to be installed before the below examples can be run. Make sure it’s in the PATH, e. g., place it in /usr/bin or /usr/local/bin.

Failure to observe this step will give you an error selenium.common.exceptions.WebDriverException: Message: ‘geckodriver’ executable needs to be in PATH.

Other supported browsers will have their own drivers available. Links to some of the more popular browser drivers follow.

Browsers      | Link
------------- | -------------
Chrome        | https://sites.google.com/a/chromium.org/chromedriver/downloads
Firefox       | https://github.com/mozilla/geckodriver/releases
Safari        | https://webkit.org/blog/6900/webdriver-support-in-safari-10/
Edge          | https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/

