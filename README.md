progress-demo-apb
===================

Progress Demo APB

## Plans
* Last Operation - Demonstrates the ASB's Last Operation Module functionality
* Custom Error Message - Demonstrates the Custom Error Message feature via termination log

## Requirements
Visit the main [APB page](https://github.com/ansibleplaybookbundle/ansible-playbook-bundle) for more information

## Parameters
N/A

## Running the application
`docker run -e "OPENSHIFT_TARGET=<openshift_target>" -e "OPENSHIFT_TOKEN=<token>" progress-demo-apb provision`

## Tearing down the application
`docker run -e "OPENSHIFT_TARGET=<openshift_target>" -e "OPENSHIFT_TOKEN=<token>" progress-demo-apb deprovision`
