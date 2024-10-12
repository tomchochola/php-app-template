# Premierstacks Public Preview

**This file has been extracted from: [https://github.com/premierstacks/php-app-template](https://github.com/premierstacks/php-app-template)**

Premierstacks is a collection of proprietary stacks and templates for PHP, JavaScript, TypeScript, React, and Laravel. Because these repositories are private and accessible only through a valid license, we offer this public preview to provide transparency and allow potential users to review the content before making a purchase.

By extracting key documentation and selected sample files to public repositories, we ensure that you can evaluate the quality, structure, and approach of Premierstacks without needing full access. This way, you can make an informed decision about whether our solutions are the right fit for your projects.

To access the complete repositories, along with continuous updates and premium support, a valid Premierstacks license is required.

**Purchase a license here: [GitHub Sponsors](https://github.com/sponsors/tomchochola).**

---

**Original content starts here!**

---

# [PHP App Template](https://github.com/premierstacks/php-app-template) by [Tomáš Chochola](https://github.com/tomchochola)

✨ _**Clone and Win!**_

The PHP App Template provides a comprehensive starting point for building PHP applications. With pre-configured setups for code quality tools, linters, and testing frameworks, this template is designed to streamline development and ensure consistent standards across projects.

## What is PHP App Template?

The PHP App Template is part of the Premierstacks collection and serves as a foundational structure for creating PHP applications. It comes pre-configured with various tools and packages, including code quality checkers, static analysis, automatic formatting, and unit testing, making it an ideal starting point for any PHP-based project.

The template includes configurations for popular tools like PHPStan, ESLint, Prettier, and PHP CS Fixer, along with dotfiles for common project settings such as .editorconfig, .gitignore, and .gitattributes. It also provides a structured Makefile for common commands and environment provisioning, enabling you to quickly set up local, testing, development, staging, and production environments.

This template’s flexibility allows developers to easily customize or remove components to fit specific project needs. Whether you’re building a pure PHP application or integrating with frameworks like Laravel, the PHP App Template is designed to save time, maintain consistency, and ensure high code quality throughout the project’s lifecycle.

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

# images/assets compression
make compress
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
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .php-cs-fixer.php
├── .prettierignore
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

4 directories, 19 files
```
