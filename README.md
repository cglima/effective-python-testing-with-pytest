# Effective Python Testing With Pytest

## We will learn

- [ ] What benefits pytest offers.
- [ ] How to ensure your tests are stateless.
- [ ] How to make repetitious tests more comprehensible.
- [ ] How to run subsets of tests by name or custom groups.
- [ ] How to create and maintain reusable testing utilities.

[Effective Python Testing With Pytest - Real Python](https://realpython.com/pytest-python-testing/#how-to-install-pytest)

### Less Boilerplate

Most functional tests follow the **Arrange-Act-Assert** model:

1. **Arrange**, or set up, the conditions for the test
2. **Act** by calling some function or method
3. **Assert** that some end condition is true

- Using pytest we just need to include a function **test_** prefix. Dont´need to deal with any imports or classes.
- Using pytest we can use the **assert** word, don´t need to remember all the different **self.assert* methods as like unittest.
- Using pytest can write an expression that we expect to evaluate to **True**.

> Using pytest eliminate a lot of boilerplate and provides much more detailed and easy-to-read output.

The output then indicates the status of each test using a syntax similar to unittest:

- **A dot (.)** means that the test passed.
- **An F** means that the test has failed.
- **An E** means that the test raised an unexpected exception.
