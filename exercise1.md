In Python application development, several common steps are typically involved in a Continuous Integration (CI) setup. These steps include linting, testing, and building.

For linting, Python developers often employ tools like Flake8, Pylint, and Black. Flake8 and Pylint analyze code for style and potential errors, while Black takes care of formatting code.

For testing the Python ecosystem offers tools such as pytest, unittest, and nose2. These frameworks facilitate the creation and execution of test suites, making sure all code is functional.

Building the application can be managed using tools like setuptools, distutils, and poetry. These tools help package the code into distributable formats.

Besides Jenkins and GitHub Actions, alternatives for setting up CI in Python projects include Travis CI and CircleCI. These platforms offer similar capabilities, allowing teams to automate their CI processes.

The choice between a self-hosted or cloud-based CI environment depends on factors like infrastructure management, scalability needs, and resource availability. Self-hosted solutions provide control but require maintenance and resources. Cloud-based options, like Travis CI or GitHub Actions, offer convenience and scalability but rely on external services.

The "optimal" setup depends also on things like the team's familiary with managing the infrastructure, possible budget constraints, desired level of control, and the project's technical needs.
