# cucumber-cypress-issue
A simple example of a Cypress project using Cucumber which is failing at the time of its creation.

## to run and fail
yarn --pure-lock (or just yarn at this time)\
yarn cypress run

## to run successfully
rm -rf node_modules\
cp working_yarn.lock yarn.lock\
yarn --pure-lock\
yarn cypress_run
