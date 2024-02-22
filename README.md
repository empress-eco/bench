<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" height="128">

  EMPRESS Bench is a powerful command-line utility built to simplify the installation, update, and management of multiple application sites on [*nix systems](https://en.wikipedia.org/wiki/Unix-like). It's an ideal tool for developers and system administrators seeking to streamline their workflow in both development and production environments.
</div>

**Project Links**:
- [Report a Bug](https://github.com/empress-eco/bench/issues)
- [Request a Feature](https://github.com/empress-eco/bench/issues)
- [Clone the Repository](https://github.com/empress-eco/bench.git)
- [Documentation](https://grow.empress.eco/)

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Technical Stack and Setup Instructions](#technical-stack-and-setup-instructions)
- [Usage](#usage)
- [Custom Bench Commands](#custom-bench-commands)
- [Guides](#guides)
- [Resources](#resources)
- [Contribution Guidelines](#contribution-guidelines)
- [Releases](#releases)
- [License and Acknowledgements](#license-and-acknowledgements)

## Technical Stack and Setup Instructions

EMPRESS Bench is primarily built with Python and supports both Development and Production environments. The installation of these environments can be achieved through either a Containerized Installation or a Manual Installation. 

For Production environments, we recommend using a Docker-based setup, while for Development environments, you may choose either method. 

To get started, clone the repository using the following command:

```sh
$ git clone https://github.com/empress-eco/bench.git
```

Please refer to our comprehensive [Installation Guide](https://grow.empress.eco/) for detailed instructions.

## Usage

Here are some basic commands to get you started with EMPRESS Bench:

- Create a new bench: `bench init [bench-name]`
- Add a site under the current bench: `bench new-site [site-name]`
- Download and add applications to the bench: `bench get-app [app-name] [app-link]`
- Install apps on a particular site: `bench --site [site-name] install-app [app-name]`
- Start bench (only for development): `bench start`

For more in-depth information on commands and their usage, please refer to our [Commands and Usage Guide](https://github.com/empress-eco/bench/blob/develop/docs/commands_and_usage.md).

## Custom Bench Commands

Customize your Bench experience by adding your own commands. Follow our [Guide on Adding Custom Bench Commands](https://github.com/empress-eco/bench/blob/develop/docs/bench_custom_cmd.md) for more details.

## Guides

We provide comprehensive guides on various topics such as configuring HTTPS, diagnosing the scheduler, changing the hostname, and more. Explore these [here](https://Empress.io/docs/user/en/bench/guides).

## Resources

Check out our [Bench Resources](https://Empress.io/docs/user/en/bench/resources) for a Bench Commands Cheat Sheet, information on Background Services, Bench Procfile, and more!

## Contribution Guidelines

To contribute to the development of EMPRESS Bench, please follow these steps:
1. Fork this repository.
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request.

For more detailed instructions, please refer to our [Contribution Guide](https://github.com/empress-eco/bench/CONTRIBUTING.md).

## Releases

You can access Bench's version information via `bench.VERSION` in the package's __init__.py file. For more information, check out our [Releases](https://github.com/empress-eco/bench/releases) section.

## License and Acknowledgements

This project is licensed under the terms of the MIT License.

We express our deepest gratitude to the Empress Community for their foundational contributions to this project. Their innovative tools and unwavering support have been instrumental in making this project a success.