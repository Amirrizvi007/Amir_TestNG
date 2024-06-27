Selenium, Java, TestNg Automation Framework.
POM implementation along with page factory, java and maven.

Forlder Structure
  > src/main/java
    >actionhelper > contains methods like custom, click, clear, mouse-actions, javascript-executor methods, windowhandel etc.
    >baselibrary > base class webdriver implementation, driver quiting, handeling cross browser etc.
    >extentlisteners > implementation of ITestListeners and created extent manager.
    >utilities > different classes to handel data-driven testing, excel sheet reader, screenshot handeling, wait utilities and property reader etc.
  >src/test/java
    > pageHelper > Contains different page classes for different pages
    > testScript > contains Test class for different test modules
  >src/test/resources > contains data sheets,config file and other requrire files.


execution:
> clone or download the project.
> to execute test classes user testng.xml file.
> all execution report i.e Extent-Report getting stored in reports folder. 

