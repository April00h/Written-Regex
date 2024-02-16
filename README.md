# Written-Regex

## Table of Contents
- [Summary](#summary)
- [Features ](#features)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)
- [License](#license)

### Summary 

Ensuring the accuracy of user-provided email addresses is fundamental to the functionality and security of web applications. This project offers a regex-based approach to address this need. The regex is designed to cover the basics of email validation, providing a starting point for developers who want a straightforward yet effective solution.



## User Story

AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines

## Acceptance Criteria

GIVEN a regex tutorial
WHEN I open the tutorial
THEN I see a descriptive title and introductory paragraph explaining the purpose of the tutorial, a summary describing the regex featured in the tutorial, a table of contents linking to different sections that break down each component of the regex and explain what it does, and a section about the author with a link to the author’s GitHub profile
WHEN I click on the links in the table of contents
THEN I am taken to the corresponding sections of the tutorial
WHEN I read through each section of the tutorial
THEN I find a detailed explanation of what a specific component of the regex does
WHEN I reach the end of the tutorial
THEN I find a section about the author and a link to the author’s GitHub profile



## Usage 

To use the provided regex for email validation in your project, simply incorporate it into your code. You can adapt it to match your specific requirements or use it as is for a quick and reliable email validation.

```javascript

const emailRegex = /^[\w.-]+@[a-zA-Z\d.-]+\.[a-zA-Z]{2,}$/;

const isValidEmail = emailRegex.test('user@example.com');

console.log(isValidEmail); 



## Contributors
[April Hunt](https://github.com/April00h)


## Questions
Please reach out with any questions or concerns: [E-mail](mailto:), [E-mail](mailto:aprilhunt00.ah@gmail.com)

## License 
This project is licensed under the MIT License.
