# Bruno POC
[Bruno](https://www.usebruno.com/) collection for investigating its features in an open-source package. Collection is located in the [httpbin.org](/httpbin.org/) folder.
  
## Application Under Test
[https://httpbin.org](https://httpbin.org) is used for testing different scenarios, such as authentication methods, status codes, HTTP methods, etc.

## Getting Started
* Download and install [Bruno](https://www.usebruno.com/)
* Clone this Git repository to your machine:
  ```shell
  git clone https://github.com/iriiiina/bruno-poc.git
  ```
* Open Bruno, click on the 'Open Collection' button on the start page, and open [httpbin.org](/httpbin.org/) folder in the cloned Git repo
* You are now ready to run existing requests or add new ones to the collection!

## Run Tests In CLI
You need to install `bru` tool to run tests in CLI - see official documentation [Bruno CLI](https://docs.usebruno.com/bru-cli/overview) for details.

After `bru` is installed, run following command in `httpbin.org/` folder:
```shell
bru run --env service
```

## Results and HTML Report
The final HTML report is located in the collection folder and can also be viewed in a browser here: [https://iriiiina.github.io/bruno-poc/httpbin.org/report.html](https://iriiiina.github.io/bruno-poc/httpbin.org/report.html).

To generate the HTML report, run the following command in the `httpbin.org/` folder:
```shell
bru run --env service --reporter-html report.html
```

## Contributing
* If you wish to commit your changes, please use [Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)
* Follow the same folder structure and terminology as seen on the [https://httpbin.org](https://httpbin.org) page
* Generate and commit the HTML report after making all your changes
* Follow best practices for [writing commit messages](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53)

## Project Status
This repository is not highly active but is used occasionally and will likely be updated a few times per year.
