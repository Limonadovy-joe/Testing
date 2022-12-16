# Software Testing
is the act of examining the artifacts and the behavior of the software under test by validation and verification. Software testing can provide objective,
independent information about the quality of software and risk of its failure to users or bussines.

**Testing approach:**
- [**The box approach**](#the-box-approach)
  - [White box testing](#white-box-testing)
  - [Black box testing](#black-box-testing)
  
**Testing techniques and tactics:**
- [Regression testing](#regression-testing)
  
**Testing frameworks:**
- [**Jest**](#jest)
  - [Mocking](#mocking)
    - [Mock functions](#mock-functions)
    - [Manual Mocks](#manual-mocks)

# **The box approach**
Software testing methods are traditionally divided into white- and black-block testing.These two approaches are used to describe the point of view that 
the tester takes when designing test cases. A hybrid approach called grey-box testing may also applied to software testing methodology.

## White box testing
White box testing also know as clear box testing verifies the internal structures or workings of a program, as opposed to the functionality exposed
to the end-user. The tester chooses inputs to exercise paths through the code and determine the appropriate outputs.
While white-box testing can be applied at the unit,integration and system levels of the software testing, it is usually done at the unit level.

Techniques used in white-box testing include:
- **API testing** 
  - testing of the app using public and private APIs
  - Api testing is performed on APIs that the development team produces as well as APIs that the team consumes within their app including
  thid-party libs
  - **Types of API testing**: unit testing, functional testing(often using unit tests as building blocks for end-to-end tests), regression testing
- **Code coverage** 
  - is a percentage measure
  - creating tests to satisfy some criteria of code coverage
  - a program with high test coverage has a more of its source code executed during testing, which implies it has a lower chance to contain undetected 
  bugs compared to a program with low test coverage
  - **Many different metrics can be used to calculate test coverage**: function coverage(Has each function been called?), 
  statement coverage(Has each statement been executed?)
  
## Black box testing
Black-box testing also known as functional testing treats the software as a black box, examining functionality wihnout any knowledge of internal implementation.
The testers are only aware of what the software is supposed to do, not how it does it

## Regression testing 
- focuses on finding defects after a major code change has been done into the codebase
- common methods of regression testing include re-running previous sets of test cases and checking whether previously  fixed faults have re-emerged



## **Jest**
a

### Mocking
aa

#### Mock functions
a

#### Manual Mocks

  
  
