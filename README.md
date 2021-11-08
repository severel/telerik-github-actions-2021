# telerik-github-actions-2021
A repository created for practicing Github Actions  
Feel free to fork this repository and work in the forked version.

# Play
1. Create pre-build stage to print information

* Add environment variables:
```
Workflow:
WORKSPACE_ENVIRONMENT_VARIABLE: 'custom workspace environment variable'

Job:
JOB_ENVIRONMENT_VARIABLE: 'custom job environment variable for ubuntu'

Step:
STEP_ENVIRONMENT_VARIABLE: 'custom step environment variable for bash'
```
Print the environment variables.

* Add secret
```
PASSWORD
```
Print the secret.

2. Create parallel checks for style and code lint

3. Build stage to depend on lint and style

4. Build stage to upload artifact
```
upload factorial.py
```
5. Unit test to depend on build stage

6. Make deploy stage to depend on unit-test

7. Add style check with python 2.7, 3.8, 3.9

8. Add SAST with SonarCloud after unit-tests

9. Add database integration

10. Create workflow for pull_request - excluding the deploy step

11. Scheduled pipeline for Snyk - scan once a day

