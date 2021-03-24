# rb-webcomponent-issue-demo project

used for code examples of possible [rb-web-components](https://github.com/redbullmediahouse/rb-web-components) [issues/bugs](https://github.com/redbullmediahouse/rb-web-components/issues)

---

# Issue: template

## Description
Description of the issue.

## How to reproduce
Description how to reproduce.

---

## Requirements

* Node v14 or above
* Rbmh Artifactory set-up (see below)

## Setup RBMH-Artifactory

1. go to [your artifactory profile](https://artifactory.redbullmediahouse.com/webapp/#/profile)
2. create an api key
3. store the following within your shellscript (.bashrc):

````
export RBMH_ARTIFACTORY_PASSWORD=YOUR_PASSWORD
export RBMH_ARTIFACTORY_USERNAME=YOUR_USERNAME
export RBMH_ARTIFACTORY_EMAIL=YOUR_EMAIL
````

## Installation

Use the package manager [npm](https://www.npmjs.com/package/npm) to install dependencies.

```bash
npm install
```

## Usage/Run

1.  Clone this repo using `git clone https://github.com/nd-ffx/rb-webcomponent-issue-demo`
2.  Move to the appropriate directory: `cd rb-webcomponent-issue-demo`
3.  Checkout branch for specific issue (unless you want to use the template at master), eg. `issue-898`
4.  Run ```npm install``` to install the dependencies
5.  Run ```npm start``` to serve the app to [localhost:5000](http://localhost:5000/)
6.  Follow 'How to reproduce' stated above, to reproduce the issue
