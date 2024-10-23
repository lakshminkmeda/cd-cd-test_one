deploy_website_s3_with_tests:
  - Uses code from https://gitlab.com/gitlab-course-public/freecodecamp-gitlab-ci (@ Velentin Despa).
  - Builds a website, tests the existence of a html file, deploys to S3 in a staging environment and then to a production environment.
  - uses variables in environments and the repository as well.
    
artifact_test:
  - Simple test to verify artifact upload and download between jobs.

Website_test:
  - Test to build a website and run tests.
