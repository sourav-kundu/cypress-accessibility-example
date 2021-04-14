# Cypress accessibility example with BrowserStack

[![vercel](https://badgen.net/badge/icon/Vercel?icon=zeit&label&color=black&labelColor=black)](https://cypress-accessibility-example.vercel.app/) [![Twitter Follow](https://img.shields.io/twitter/follow/leozera?label=Follow%20on%20Twitter)](https://twitter.com/leozera/)

Example repository showing how to run Accessibility tests using cypress and cypress-axe on BrowserStack cloud.

Follow the steps below to run basic accessibility tests on a demo web application:
1. Clone this repository
2. Run `npm install` to install all dependencies
3. Run `npm run serve` which will start a local server on `http://localhost:8000`
4. Put your BrowserStack credentials in the file `browserstack.json`
5. Run `npm install -g browserstack-cypress-cli` if you do not have the CLI installed already
6. Run `browserstack-cypress run --sync` which will run the accessibility tests on BrowserStack on the browsers listed in the `browserstack.json` file.


This is the [step by step post](https://leonardofaria.net/2020/08/13/automating-accessibility-tests-with-cypress/) in [the blog](https://leonardofaria.net) of the original creator of the example which covers cypress + cypress-axe.