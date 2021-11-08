# telerik-github-actions-2021
A repository created for practicing Github Actions  
Feel free to fork this repository and work in the forked version.

1 Create pre-build stage to print information
1.1 Add environment variables:
Workflow:
WORKSPACE_ENVIRONMENT_VARIABLE: 'custom workspace environment variable'

Job:
JOB_ENVIRONMENT_VARIABLE: 'custom job environment variable for ubuntu'

Step:
STEP_ENVIRONMENT_VARIABLE: 'custom step environment variable for bash'

Print the environment variables.

1.2 Add secret
PASSWORD

Print the secret.

# Create parallel checks for style and code lint

# Build stage to depend on lint and style

# Build stage to upload artifact
upload factorial.py

# Unit test to depend on build stage

# deploy stage to depend on unit-test

# Add style check with python 2.7, 3.8, 3.9

# Add SAST with SonarCloud after unit-tests

# Add database integration

# Create workflow for pull_request - excluding the deploy step

