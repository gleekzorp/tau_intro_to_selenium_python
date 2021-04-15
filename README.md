# Test Automation University Selenium Webdriver with Python

https://testautomationu.applitools.com/selenium-webdriver-python-tutorial/

# Docs

- **Teacher's Repo:**
  - https://github.com/AndyLPK247/tau-intro-selenium-py
- **Selenium WebDriver:**
  - https://selenium-python.readthedocs.io/
  - https://selenium-python.readthedocs.io/api.html
  - https://selenium-python.readthedocs.io/waits.html
  - https://www.selenium.dev/documentation/en/
  - https://github.com/SeleniumHQ/selenium/wiki/Grid2
- **Pytest:**
  - https://docs.pytest.org/en/stable/
  - https://docs.pytest.org/en/stable/parametrize.html
  - https://github.com/pytest-dev/pytest-xdist

# Deeper Dives / Recommended Tutorials

- https://testautomationu.applitools.com/web-element-locator-strategies/
- https://testautomationu.applitools.com/ai-for-element-selection-erasing-the-pain-of-fragile-test-scripts/
- https://testautomationu.applitools.com/scaling-tests-with-docker/
- https://testautomationu.applitools.com/behavior-driven-python-with-pytest-bdd/
- https://automationpanda.com/2018/01/21/to-infinity-and-beyond-a-guide-to-parallel-testing/
- https://automationpanda.com/tag/gherkin/

# Setup

- Create a Virtual Environment

```
$ python -m venv venv
```

- Activate the Virtual Environment

```
MAC
$ source venv/bin/activate
(venv) $ _

PC
$ venv\Scripts\activate
(venv) $ _
```

- Install the packages

```
(venv) $ pipenv install
```

# Running Tests

- Run all tests

```
(venv) $ pipenv run python -m pytest
```

- Run all tests in parallel

```
(venv) $ pipenv run python -m pytest -n NumberOfThreads
(venv) $ pipenv run python -m pytest -n 3
```

# Extra Challenges:

The guided course covered one very basic search test, but DuckDuckGo has many more features. Try to write some new tests for DuckDuckGo independently. Here are some suggestions:

- search for different phrases
- search by clicking the button instead of typing RETURN
- click a search result
- expand "More Results" at the bottom of the result page
- verify auto-complete suggestions pertain to the search text
- search by selecting an auto-complete suggestion
- search a new phrase from the results page
- do an image search
- do a video search
- do a news search
- change settings
- change region

These tests will require new page objects, locators, and interaction methods. See how many tests you can automate on your own! If you get stuck, ask for help.

You could also add tests for other web apps, too.

https://github.com/AndyLPK247/tau-intro-selenium-py#independent-exercises
