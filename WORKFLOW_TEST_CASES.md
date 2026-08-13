# CI/CD Workflow Test Cases

## Project
Raju Hisaab

## CI/CD Tool
GitHub Actions

## Deployment Platform
GitHub Pages

| TC ID | Test Case | Test Steps | Expected Result |
|------|-----------|------------|-----------------|
| TC01 | Verify workflow triggers on push | Push a change to the main branch | GitHub Actions workflow starts automatically |
| TC02 | Verify index.html exists | Run the CI workflow | CI verifies that index.html exists |
| TC03 | Verify HTML structure | Run the CI workflow | DOCTYPE, HTML, HEAD, BODY and SCRIPT tags are detected |
| TC04 | Verify application title | Run the CI workflow | Raju Hisaab title is detected successfully |
| TC05 | Verify crop functionality exists | Run the CI workflow | Add Crop functionality is detected |
| TC06 | Verify expense functionality exists | Run the CI workflow | Add Expense functionality is detected |
| TC07 | Verify localStorage usage | Run the CI workflow | localStorage implementation is detected |
| TC08 | Verify JavaScript functions | Run the CI workflow | Required JavaScript functions are detected |
| TC09 | Verify CI-to-CD dependency | Push valid code to main | CD starts only after CI succeeds |
| TC10 | Verify deployment | Push valid code to main | Website is deployed to GitHub Pages |
| TC11 | Verify Pull Request CI | Create a pull request to main | CI runs automatically |
| TC12 | Verify failed CI prevents deployment | Introduce an invalid/missing required element | CI fails and CD does not execute |
| TC13 | Verify updated deployment | Modify index.html and push to main | Updated website is deployed automatically |
| TC14 | Verify import/export functionality | Open deployed website and test Import/Export | Data import/export functionality works |
| TC15 | Verify search and sorting | Open deployed website and test search/sort | Crops can be searched and sorted correctly |
