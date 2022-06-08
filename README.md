# Selenium

Selenium Webdriver is an open-source collection of APIs which is used for testing web applications. The Selenium Webdriver tool is used for automating web application testing to verify that it works as expected or not. It mainly supports browsers like Firefox, Chrome, Safari and Internet Explorer. It also permits you to execute cross-browser testing.



#Following programming languages are supported by WebDriver
Java
.Net
PHP
Python
Perl
Ruby


# Locaters in selenium

**By.className
**finds elements based on the value of the “class” attribute	findElement(By.className(“someClassName”))
By.cssSelector	finds elements based on the driver’s underlying CSS Selector engine	findElement(By.cssSelector(“input#email”))
By.id	locates elements by the value of their “id” attribute	findElement(By.id(“someId”))
 
By.linkText	finds a link element by the exact text it displays	findElement(By.linkText(“REGISTRATION”))
 
By.name	locates elements by the value of the “name” attribute	findElement(By.name(“someName”))
 
By.partialLinkText	locates elements that contain the given link text	findElement(By.partialLinkText(“REG”))
 
By.tagName	locates elements by their tag name	findElement(By.tagName(“div”))
 
By.xpath	locates elements via XPath	findElement(By.xpath(“//html/body/div/table/tbody/tr/td[2]/table/
tbody/tr[4]/td/table/tbody/tr/td[2]/table/tbody/tr[2]/td[3]/ form/table/tbody/tr[5]”))
