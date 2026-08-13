# CI/CD Workflow Test Cases

## Project
CROP

## Workflow
CROP CI/CD Pipeline

| TC ID | Test Case | Steps | Expected Result |
|------|-----------|-------|-----------------|
| TC01 | Verify workflow triggers on push | Push a change to main branch | GitHub Actions workflow should start automatically |
| TC02 | Verify index.html exists | Run CI workflow | Workflow should verify that index.html exists |
| TC03 | Verify HTML structure | Run CI workflow | Workflow should verify html, head and body tags |
| TC04 | Verify non-empty HTML file | Run CI workflow | Workflow should pass when index.html contains content |
| TC05 | Verify CI failure for missing index.html | Temporarily remove index.html and push | CI should fail and deployment should not execute |
| TC06 | Verify CD runs after successful CI | Push valid code to main | Continuous Deployment should execute after CI passes |
| TC07 | Verify GitHub Pages deployment | Successfully run CD | Website should be deployed to GitHub Pages |
| TC08 | Verify pull request workflow | Create a pull request to main | CI should run for the pull request |
| TC09 | Verify deployment dependency | Create a valid push to main | CD should wait for CI to complete successfully |
| TC10 | Verify updated website | Modify index.html and push to main | Updated website should be deployed automatically |
