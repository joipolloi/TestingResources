# TestingResources
A collection of resources to improve and assist manual Front End testing of projects.
Currently this is just a list of potential resources that have yet to be investigated.
Feel free to add new tools or have a lok at any and review them.

## Automation
* [Browserstack Automation](https://www.browserstack.com/automate) : Executes Selenium scripts across multiple browsers. As yet untested but has good CI intergation. Selenium integration also allows other tools such as [The Glen Framework](http://galenframework.com/)
* [CasperJS]() : A headless web browser allowing you to automate interactions in a site and export screenshots of the results/evaluate assertions etc. See [this link](https://www.helpscout.net/blog/functional-testing-casperjs/) for a good example

## Accessibility
* [Tota11y](http://khan.github.io/tota11y/): Javascript based accesibility tester. Good for manual testing of single pages. Very useful screen reader wand feature (currently experimental) lets you see what a screen reader will read.
* [The A11y Machine](https://github.com/liip/TheA11yMachine) : Automated web page accessibility crawler.
Generates quite a nice HTML report but is quite verbose. Could do with some work to prune severity levels etc. Suggest using this on upcoming projects.
* [pa11y](https://github.com/pa11y/pa11y) : Automated accessibility testing
Currently untested

## Other Tools
* [Gremlins.js](https://github.com/marmelab/gremlins.js) : Monkey testing - simulate random user input.
Probably quite niche but if your site has a lot of user interaction then this will probably catch any corner cases.
* [BackstopJS](https://garris.github.io/BackstopJS/) : CSS regression tool - visually identify regressions. Needs some work into integrating into a workflow but tests on the command line seem promising.
