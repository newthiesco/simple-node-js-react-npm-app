# simple-node-js-react-npm-app

This repository is for the [Build a Node.js and React app with npm](https://jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/)
tutorial in the [Jenkins User Documentation](https://jenkins.io/doc/).

The repository contains a simple Node.js and React application which generates a web page with the content "Welcome to React" and is accompanied by a test to
check that the application renders satisfactorily.

The `jenkins` directory contains an example of the `Jenkinsfile` (i.e. Pipeline)
you'll be creating yourself during the tutorial and the `scripts` subdirectory
contains shell scripts with commands that are executed when Jenkins processes
the "Test" and "Deliver" stages of your Pipeline.

Install Node.js and npm on the Jenkins Server

If Node.js and npm are not installed, you need to install them on the Jenkins server. Here are the steps for common operating systems:
###
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
###

Ensure npm Is in the PATH

export PATH=$PATH:/usr/local/bin

Replace /usr/local/bin with the directory where npm is installed, which you can find by running:

which npm

After updating the PATH, make sure to reload the profile:

source ~/.bashrc

https://www.jenkins.io/doc/tutorials/build-a-node-js-and-react-app-with-npm/
