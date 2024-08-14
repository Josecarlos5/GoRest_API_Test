
# GoRest API Tests

## Prerequisites
- Postman installed on your machine.
- Internet connection.

## Setup Instructions
1. Open Postman.
2. Import the collection:
   - Click on `File` -> `Import`.
   - Select `GoRest_API_Tests.postman_collection.json`.
3. Import the environment:
   - Click on `File` -> `Import`.
   - Select `GoRest_API.postman_environment.json`.

## Running the Tests
1. Select the `GoRest API` environment from the environment dropdown.
2. Open the `GoRest API Tests` collection.
3. Click on the `Run` button to open the collection runner.
4. Click `Start Test` to run the tests.

## Notes
- The tests will create a user, verify the user creation, and then delete the user.
- Ensure the token in the environment file is valid before running the tests.
