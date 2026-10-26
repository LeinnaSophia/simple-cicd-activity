# Simple CI/CD Activity

**Student Name:** Leinna Sophia
**Published Website:** https://leinnasophia.github.io/simple-cicd-activity/

## Project Overview
This repository demonstrates a complete CI/CD pipeline using GitHub Actions. 
- **Continuous Integration (CI):** Automatically compiles Java code and runs 3 tests whenever changes are pushed.
- **Continuous Deployment (CD):** Automatically deploys the HTML website in the `/site` folder to GitHub Pages, but only if the Java tests pass successfully.

## Repository Structure
- `.github/workflows/cicd.yml`: The GitHub Actions pipeline configuration.
- `src/Main.java` & `src/MainTest.java`: The Java application and automated tests.
- `site/index.html`: The website that gets deployed.
