The project autotests are implemented using Selenium Webdriver+Python+Pytest+Allure Framework,
<br>based on a Page Object pattern for this <a href="http://selenium1py.pythonanywhere.com/en-gb/">Resource</a>: 

## Getting started

1. clone the project repository:
```
git clone https://github.com/ihorvoitkiv/WebUI_test_automation.git
cd WebUI_test_automation
```
2. create and activate a virtual environment:
```
python3 -m venv selenium_env
source selenium_env/bin/activate
```
3. install the requirements:
```
pip install -r requirements.txt
```
4. to enable Allure listener to collect results during the test execution simply add --alluredir option and provide path to the folder where results should be stored. E.g.:
```
pytest --alluredir=allure-results
```
5. To see the actual report after your tests have finished, you need to use Allure commandline utility to generate report from the results:
```
allure serve ./allure-results
```
6. deactivate a virtual environment:
```
deactivate
```

Thanks,

<img src="https://www.google.com/search?q=+cat+is+coding+gif&tbm=isch&ved=2ahUKEwiWj-GJvb3qAhUDW5oKHd81BzEQ2-cCegQIABAA&oq=+cat+is+coding+gif&gs_lcp=CgNpbWcQAzIECCMQJzoECAAQEzoGCAAQBxAeOggIABAIEAcQHlDjU1iRfWCIgAFoAnAAeACAAWCIAdwGkgECMTCYAQCgAQGqAQtnd3Mtd2l6LWltZw&sclient=img&ei=-KMFX5azBYO26QTf65yIAw&bih=721&biw=1440#imgrc=aHKFqglWuSRcqM">