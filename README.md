# [PHP App Template](https://github.com/premierstacks/php-app-template) by [Tomáš Chochola](https://github.com/tomchochola)

✨ _**Clone and Win!**_

## What is PHP App Template?

## What is Tomchochola

[https://gitub.com/tomchochola](https://gitub.com/tomchochola)

This is my personal GitHub profile, where you’ll find public documentation and sample repositories for proprietary packages and templates from Premierstacks. These public repositories are designed to give you an overview of the best practices and high-quality code I follow in all my projects.

## What is Premierstacks

[https://gitub.com/premierstacks](https://gitub.com/premierstacks)

Premierstacks is a collection of exclusive, proprietary stacks and templates for PHP, JavaScript, TypeScript, React, and Laravel. It was created to address the common pain points developers face with many open-source projects—quality, consistency, and maintainability. With Premierstacks, you get high-quality tools built with strict attention to detail, designed to help you build and maintain better projects, faster.

## Why Premierstacks?

I created Premierstacks because I wasn’t satisfied with the quality of many open-source projects. Maintaining high-quality code and ensuring long-term reliability is challenging when you’re not earning from the product. When you pay for something, it means the creator truly cares about its success and is committed to delivering the best possible outcome.

Like Apple’s approach with their closed ecosystem, I believe that true excellence can only be achieved when every detail is under your control. That’s why Premierstacks is proprietary software—it's not just about providing solutions; it’s about ensuring those solutions meet the highest standards.

### Why You Should Choose Premierstacks

**🚀 Unmatched Quality**

Our solutions adhere to the highest standards, ensuring clean and maintainable code.

**⚙️ No Setup Hassles**

Pre-configured environments let you start coding immediately—no more complex setups.

**📦 Reuse Across Projects**

Each library and template is built to be reusable, reducing long-term maintenance.

**🔒 Exclusive Resources**

Premierstacks offers tools you won’t find in typical open-source collections.

**🛠️ Always Up-to-Date**

Receive continuous updates and new features, keeping your projects current.

**💪 Expert Creators**

Developed by experienced professionals dedicated to quality and excellence.

## License

**© 2024–Present Tomáš Chochola <chocholatom1997@gmail.com>. All rights reserved.**

This software is proprietary and licensed under specific terms set by its owner.<br />
Any form of access, use, or distribution requires a valid and active license.<br />
For full licensing terms, refer to the LICENSE.md file accompanying this software.<br />

**Purchase a license here: [Github Sponsors](https://github.com/sponsors/tomchochola)**

**See full terms here: [/LICENSE.md](/LICENSE.md)**

## Preconfigured Features

This template includes the following features:

**1. [https://github.com/premierstacks/php-stack](https://github.com/premierstacks/php-stack)**

php utility library

**2. [https://github.com/premierstacks/phpstan-stack](https://github.com/premierstacks/phpstan-stack)**

phpstan template, [/phpstan.neon](/phpstan.neon)

**3. [https://github.com/premierstacks/prettier-stack](https://github.com/premierstacks/prettier-stack)**

prettier template, [/prettier.config.js](/prettier.config.js), [/.prettierignore](/.prettierignore)

**4. [https://github.com/premierstacks/eslint-stack](https://github.com/premierstacks/eslint-stack)**

eslint template, [/eslint.config.js](/eslint.config.js)

**5. [https://github.com/premierstacks/php-cs-fixer-stack](https://github.com/premierstacks/php-cs-fixer-stack)**

php-cs-fixer template, [/.php-cs-fixer.php](/.php-cs-fixer.php)

**6. phpunit**

unit testing, [/phpunit.xml](/phpunit.xml), [/tests](/tests)

**7. dot files**

[/.editorconfig](/.editorconfig), [/.gitignore](/.gitignore), [/.gitattributes](/.gitattributes)

**8. Makefile**

CLI commands implemented in using make, [/Makefile](/Makefile)

**9. Composer**

php package manager, [/composer.json](/composer.json)

**10. NPM**

node package manager, [/package.json](/package.json)

**11. entrypoint**

public entrypoint, [/public/index.php](/public/index.php)

## Getting Started

**1. Review the documentation and license**

Ensure this package fits your needs and that you agree with the terms.

**2. Obtain a license**

**Purchase a license here: [Github Sponsors](https://github.com/sponsors/tomchochola)**

**3. Project Creation**

Use the `Use this template` button on the GitHub repository page to create a new repository from this template.

Or clone the repository using the following command:

```bash
git clone https://github.com/premierstacks/php-app-template.git php-app
```

**4. Customize Your Project**

Explore the generated repository, remove unnecessary components and adjust it to fit your project's needs.

**5. CLI**

Available make commands:

```bash
# provision for local environment
make local

# provision for testing (CI) environment
make testing

# provision for development environment
make development

# provision for staging environment
make staging

# provision for production environment
make production

# run automatic code fixers
make fix

# run linters, static analysis, tests and audit
make check

# browser phpunit code coverage
make coverage

# clean up the project
make clean
make distclean

# run before every commit
make commit
```

## About the Creator

I'm Tomáš Chochola, a software developer dedicated to creating exclusive, enterprise-grade software solutions. I specialize in building packages and templates for PHP, JavaScript, and TypeScript, tailored to streamline development workflows, enforce best practices, and save you time.

My mission is to develop reusable solutions that enhance code quality, boost productivity, and ensure that projects remain maintainable and scalable over the long term.

### Specializations

**Backend Development:** Expert in PHP and Laravel<br />
**Frontend Development:** Mastery in TypeScript, React, and JavaScript<br />
**DevOps:** Proficient in managing Ubuntu and AWS environments<br />
**Security:** Focused on implementing best practices and enforcing code standards<br />
**Tooling:** Extensive experience with ESLint, Prettier, PHP CS Fixer, Stylelint, and PHPStan<br />
**Reusable Solutions:** Creating templates and configuration stacks for optimized development<br />
**Development Environments:** Fluent in Windows 11 and Ubuntu (WSL2)<br />

## Contact

**📧 Email: <chocholatom1997@gmail.com>**<br />
**💻 Website: [https://premierstacks.com](https://premierstacks.com)**<br />
**👨 GitHub Personal: [https://github.com/tomchochola](https://github.com/tomchochola)**<br />
**🏢 GitHub Organization: [https://github.com/premierstacks](https://github.com/premierstacks)**<br />
**💰 GitHub Sponsors: [https://github.com/sponsors/tomchochola](https://github.com/sponsors/tomchochola)**<br />

## Tree

The following is a breakdown of the folder and file structure within this repository. It provides an overview of how the code is organized and where to find key components.

```bash
.
├── AUTHORS.md
├── LICENSE.md
├── Makefile
├── README.md
├── composer.json
├── eslint.config.js
├── package.json
├── phpstan.neon
├── phpunit.xml
├── prettier.config.js
├── public
│   └── index.php
├── src
│   └── Main.php
└── tests
    └── Unit
        ├── MainTest.php
        └── TestCase.php

4 directories, 14 files
```
