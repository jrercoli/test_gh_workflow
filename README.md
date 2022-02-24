# test_gh_workflow
Test actions in a github workflow to implement CI/CD (AWS serverless) with 2 differents workflows:
- dev.yml, when push a commit in branch 'dev', trigger a deploy with serverless in stage dev
- workflow.yml, when push a commit in branch 'main', trigger a deploy with serverless in stage main

To run the workflows you must include your AWS credentials:
AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY
Save those in settings-secrets-actions
