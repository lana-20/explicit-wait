# Explicit Waits

* Poll for app state using client-side methods
* Can check for any state which can be determined using WebDriver functionality
* The polling functionality is built into the Python client on a class called WebDriverWait (<code>selenium.webdriver.support.wait.WebDriverWait</code>)
* WebDriverWaits have an <code>until()</code> method which takes an Expected Condition(<code>selenium.webdriver.support.expected_conditions</code>)
