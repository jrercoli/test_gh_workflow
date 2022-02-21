# test_gh_workflow
Test actions in a github workflow to implement CI/CD (AWS serverless) with 2 differents workflows:
- dev.yml, when push a commit in branch 'dev', trigger a deploy with serverless in stage dev
- workflow.yml, when push a commit in branch 'main', trigger a deploy with serverless in stage main