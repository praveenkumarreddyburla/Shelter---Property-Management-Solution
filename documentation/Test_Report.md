# Project Test Coverage and Testing Approach

## Test Coverage

Our project currently maintains a 78.61% line coverage.

## Test Cases
![Code_coverage](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/main/documentation/Codecoverage1.png)

![Code_coverage2](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/dc5f85b70c92737b06b3f92b95145057b8c4c6da/documentation/codecoverage2.png)
### Service Layer Tests

#### `Applications.test.js`
- Tests Application service module (`Application.js`) using Jest.
- Scenarios include creating, updating, and retrieving applications.
- Mocks simulate interactions with data module and database models.

![Application_service](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/dc5f85b70c92737b06b3f92b95145057b8c4c6da/documentation/Application_service.png)

![Application_service2](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/dc5f85b70c92737b06b3f92b95145057b8c4c6da/documentation/Application_service2.png)


#### `Buildings.test.js`
- Tests Buildings service module operations.
- Uses Jest for testing create, read, update, and delete operations for buildings.


![Building_Service1](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/dc5f85b70c92737b06b3f92b95145057b8c4c6da/documentation/Building_Service1.png)

![Building_Service2](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/dc5f85b70c92737b06b3f92b95145057b8c4c6da/documentation/Building_service2.png)

#### `Listings.test.js`
- Test suites for Listings Service module.
- Focuses on creating, retrieving, updating, and deleting listings.

#### `Notices.test.js`
- Tests for Notices Service module.
- Covers retrieving, creating, updating, and deleting notices.

#### `Users.test.js`
- Test suites for 'signUpUser' and 'loginUser' functions in User Service.
- Checks user creation, login, error handling, and token generation.

#### `WishList.test.js`
- Jest tests for Wish List Service module.
- Tests adding, retrieving, and removing wishlist items.

### Data Layer Tests

#### `Application.test.js`
- Tests application creation, acceptance/rejection, and retrieval.

#### `Buildings.test.js`
- Tests for building service functions.

#### `Listings.test.js`
- Jest test suite for property listing functionalities.

#### `Notices.test.js`
- Tests for notice retrieval, creation, update, and deletion.

#### `Users.test.js`
- Tests getUserByEmail and createUser functionalities.

#### `WishList.test.js`
- Tests wishlist-related functionalities.

### Integration Testing


![Integration_testing](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/f6c9206946cb7440c0b1f1b0989574b90fab577c/documentation/Integration_testing.png)

#### `ApplicationsTestingFlow.test.js`
- Tests application flow for retrieving applications.
![Application_integration_test](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/f6c9206946cb7440c0b1f1b0989574b90fab577c/documentation/Application_integration_test.png)

#### `BuildingsFlow.test.js`
- Tests building flow for retrieving buildings.

#### `ListingsFlow.test.js`
- Tests listings flow for retrieving listings.

#### `LoginFlow.test.js`
- Tests user login functionality.

#### `NewsFeedsFlow.test.js`
- Tests newsfeed flow for retrieving newsfeeds.

#### `NoticesFlow.test.js`
- Tests notices flow for retrieving notices.

#### `Signup.test.js`
- Tests signup functionality for existing users.

### TDD Approach

- The project follows the Test-Driven Development (TDD) approach from the start.
 ![TDD](https://git.cs.dal.ca/courses/2023-fall/csci-5308/Group18/-/raw/547e0b3b4b0fa8babe4e53c5f5566037f5451701/documentation/TDD.png)
---

This README provides an overview of our project's testing strategies and coverage.
