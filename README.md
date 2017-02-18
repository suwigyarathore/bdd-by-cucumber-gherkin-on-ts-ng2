# CucumberJS with Gherkin scenarios based on BDD Approach in Protractor & Angular2 on Typescript

An example project to setup CucumberJS with Gherkin scenarios based on Behavior-Driven development (BDD) in Protractor & Angular2 As a base for the project I've used the amazing starting pack: https://github.com/angular/quickstart.git

## Get started

```bash
# clone the repo
git clone https://github.com/suwigyarathore/bdd-by-cucumber-gherkin-on-ts-ng2 ng2-bdd-gherkin

# change directory to our repo
cd ng2-bdd-gherkin

# install the repo with npm
npm install

# start the server
npm start

# run the tests ( this will both run the E2E & unit tests )
npm run e2e
```
## BDD

In software engineering, behavior-driven development (BDD) is a software development process that emerged from test-driven development (TDD).Behavior-driven development combines the general techniques and principles of TDD with ideas from domain-driven design and object-oriented analysis and design to provide software development and management teams with shared tools and a shared process to collaborate on software development.

More info:
- https://en.wikipedia.org/wiki/Behavior-driven_development
- https://www.agilealliance.org/glossary/bdd/

## Chai & Chai as Expected

Chai is a BDD / TDD assertion library for node and the browser that can be delightfully paired with any javascript testing framework.
Chai as Promised extends Chai with a fluent language for asserting facts about promises

More info:
- http://chaijs.com/
- http://chaijs.com/plugins/chai-as-promised/


## CucumberJS

Cucumber.js is a Cucumber implementation written in pure JavaScript. It runs on Node.js, IO.js, browsers and any other JavaScript platform.

More info:
- https://cucumber.io/docs/reference/javascript
- https://github.com/cucumber/cucumber-js

## Gherkin scenarios

Gherkin is the language that Cucumber understands. It is a Business Readable, Domain Specific Language that lets you describe software’s behaviour without detailing how that behaviour is implemented.

Gherkin serves two purposes — documentation and automated tests. The third is a bonus feature — when it yells in red it’s talking to you, telling you what code you should write.

More info:
- https://github.com/cucumber/cucumber/wiki/Gherkin
