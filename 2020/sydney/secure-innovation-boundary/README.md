# Using GraphQL as a Secure Innovation Boundary and data-driven culture driver

*By Kieran Jacobsen, Rob Moore and Sam Curry*

Do these scenarios sound familiar?

* "It's hard to innovate; every time we want to access some data we need to talk to multiple teams and wait to get approval."
* "When we access our core data we need to wait for a time-constrained subject matter expert to help us out; the data schema of our core systems is hard to decipher without their help."
* "The easiest way for us to integrate with core systems is via the reporting replica databases, but now all of our systems are tightly coupled and we can't evolve our core systems."
* "Our systems integration landscape is a security nightmare, there is no cross-cutting authorisation or telemetry and we are using shared database credentials between systems that give full access to all the data."

As consultants, we've seen these problems occur commonly across multiple organisations. As it turned out, we were no exception either! We recently realised that these problems we've helped identify and solve for our customers were impacting our business, Telstra Purple, the largest Australian-owned technology services company. To address this, we took our learnings from multiple customer projects and applied them to our business. This involved using GraphQL to implement a Secure Innovation Boundary that we lovingly call Purple Graph!

In this presentation, we will describe how we went about pitching, prototyping, launching and operating Purple Graph. We will cover the learnings we've had along the way (technical and non-technical) and talk about the cultural change that we are starting to drive using this technology.

You'll leave this presentation with an understanding of the people, process and technology changes we were able to drive using this technology as well as our technical and non-technical tips to help you want to roll out a similar change to your organisation.

## Slides

Todo

## Further reading

### Server & UIs
 - [Express](https://expressjs.com/)
 - [Apollo Server](https://www.apollographql.com/docs/apollo-server/)
 - [GraphQL Playground](https://www.apollographql.com/docs/apollo-server/testing/graphql-playground/)
 - [GraphQL Voyager](https://github.com/APIs-guru/graphql-voyager#readme)
### Configuration
- [node-config](https://lorenwest.github.io/node-config/)
- [dotenv-cli](https://github.com/entropitor/dotenv-cli#readme)
### Runtime / Utility
- [DataLoader](https://github.com/graphql/dataloader)
- [Lodash](https://lodash.com/)
- [async-lock](https://github.com/rogierschouten/async-lock)
- [uuid](https://github.com/uuidjs/uuid#readme)
- [ts-node-dev](https://github.com/whitecolor/ts-node-dev#readme)
### Composition
 - [InversifyJS](http://inversify.io/)
 - [GraphQL Tools](https://github.com/ardatan/graphql-tools#readme)
 - [GraphQL Middleware](https://github.com/prisma-labs/graphql-middleware)
### Security
 - [Passport](http://www.passportjs.org/)
 - [passport-azure-ad](https://github.com/AzureAD/passport-azure-ad#readme)
 - [GraphQL Shield](https://github.com/maticzav/graphql-shield)
 - [Helmet](https://helmetjs.github.io/)
 - [snyk](https://github.com/snyk/snyk#readme)
 - [npm-audit-ci-wrapper](https://github.com/InfoSec812/npm-audit-ci-wrapper#readme)
### Observability
 - [winston](https://github.com/winstonjs/winston#readme)
 - [Application Insights for NodeJS](https://github.com/microsoft/ApplicationInsights-node.js#readme)
### Testing
 - [Mocha](https://mochajs.org/)
 - [Chai](https://www.chaijs.com/)
 - [Approvals (for NodeJS)](https://github.com/approvals/Approvals.NodeJS)
 - [Talkback](https://github.com/ijpiantanida/talkback#readme)
 - [Istanbul](https://istanbul.js.org/)
 - [Concurrently](https://github.com/kimmobrunfeldt/concurrently#readme) + [wait-on](https://github.com/jeffbski/wait-on#readme)
### VS Code Plugins
- [Test Explorer UI](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer) + [Mocha Test Explorer](https://marketplace.visualstudio.com/items?itemName=oguimbal.vscode-mocha-test-adapterhttps://github.com/hbenl/vscode-mocha-test-adapter)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)