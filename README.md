# DEVELOPMENT Repository

Integration flow:
- Trigger condition: PR with label "released" is merged into master
- Workflow:
    - Run and Build dev repo
    - Build and Execute smoke tests
    - Trigger Regression tests from Test repo
