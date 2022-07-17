# BSDEX Software Engineer in Test Challenge


Welcome to the coding challenge for the Software Engineer in Test roleat BSDEX.The goal of this challenge is to get a better idea of your skills and your general testing mindset.

## Tasks
* Create a git repository containing this README and start your implementation on a feature branch
* Create a setup for a UI testing software (open source) of your choice (please contain any additional script or instructions for installation if necessary)
* Write 10 different tests for the BSDEX Market Detail Widget
* Zip your repository and send us your solution back via mail (please Zip only those files which would be in the freshly pulled branch!)

## Market Detail Widget
The Market Detail Widget is a standalone website, which can be integrated by partners via an iframe. It can be parametrized to some extent (see below).

Example: https://widgets.bsdex.de/de/market-detail?market=btc-eur,xrp-eur

### Parameters

#### Route parameters
The widget is available in German `/de` and English `/en`. 

#### Query parameters

|Parameter|Options|Default|Description|
|---------|-------|-------|-----------|
|market | btc-eur, eth-eur, ltc-eur, xrp-eur | btc-eur |
|hide_cta | 0\|1 | 0 | Binary flag to hide the call-to-action button |
|selected_range| 24H, 1W, 1M, YTD | 1W | Sets the time range |
|ranges| 24H, 1W, 1M, YTD | _all ranges_ | Comma-separated list of symbolic date ranges going backward from the current point in time |



## Evaluation criteria

### Minimum requirements
* The solution should be implemented in either Javascript, Typescript, or Ruby
* The test suite should be executable on any platform (Windows/Mac OS/Linux)
* The project should contain a README.md file with instructions on how to install and run the test suite
* Git commit messages should be consistent and follow best practices

### Things we will take into consideration for the evaluation
* structure of your project
* structure of your code
* adaptions of best practices and common sense
* the creativity of your test scenariosGet in touch

## Get in touch
If you need any additional information or guidance, please get in touch with us!
