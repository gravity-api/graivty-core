#### [Gravity.Core](./index.md 'index')
### [OpenQA.Selenium.Extensions](./OpenQA-Selenium-Extensions.md 'OpenQA.Selenium.Extensions').[WebDriverExtensions](./OpenQA-Selenium-Extensions-WebDriverExtensions.md 'OpenQA.Selenium.Extensions.WebDriverExtensions')
## WebDriverExtensions.GetElement(OpenQA.Selenium.IWebDriver, OpenQA.Selenium.By) Method
Finds the first exists [OpenQA.Selenium.IWebElement](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.IWebElement 'OpenQA.Selenium.IWebElement') using the given method.  
```csharp
public static OpenQA.Selenium.IWebElement GetElement(this OpenQA.Selenium.IWebDriver driver, OpenQA.Selenium.By by);
```
#### Parameters
<a name='OpenQA-Selenium-Extensions-WebDriverExtensions-GetElement(OpenQA-Selenium-IWebDriver_OpenQA-Selenium-By)-driver'></a>
`driver` [OpenQA.Selenium.IWebDriver](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.IWebDriver 'OpenQA.Selenium.IWebDriver')  
This [OpenQA.Selenium.IWebDriver](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.IWebDriver 'OpenQA.Selenium.IWebDriver') instance.  
  
<a name='OpenQA-Selenium-Extensions-WebDriverExtensions-GetElement(OpenQA-Selenium-IWebDriver_OpenQA-Selenium-By)-by'></a>
`by` [OpenQA.Selenium.By](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.By 'OpenQA.Selenium.By')  
The locating mechanism to use.  
  
#### Returns
[OpenQA.Selenium.IWebElement](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.IWebElement 'OpenQA.Selenium.IWebElement')  
The first visible matching [OpenQA.Selenium.IWebElement](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.IWebElement 'OpenQA.Selenium.IWebElement') on the current context.  
#### Exceptions
[OpenQA.Selenium.WebDriverTimeoutException](https://docs.microsoft.com/en-us/dotnet/api/OpenQA.Selenium.WebDriverTimeoutException 'OpenQA.Selenium.WebDriverTimeoutException')  
Thrown when element was not found.  
### Remarks
If not provided, the default timeout is 10 seconds.  
