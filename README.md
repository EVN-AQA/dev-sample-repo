# dev-sample-repo

CICD flow:
- trigger condition: PR with label "released" is merged into master
- workflow:
    - Run and Build dev repo
    - Build and Execute smoke tests
    - Trigger Regression tests from Test repo