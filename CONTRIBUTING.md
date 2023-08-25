<<<<<<< HEAD
# Contributing to Home Assistant

Everybody is invited and welcome to contribute to Home Assistant. There is a lot to do...if you are not a developer perhaps you would like to help with the documentation on [home-assistant.io](https://home-assistant.io/)? If you are a developer and have devices in your home which aren't working with Home Assistant yet, why not spend a couple of hours and help to integrate them?

The process is straight-forward.

 - Read [How to get faster PR reviews](https://github.com/kubernetes/community/blob/master/contributors/guide/pull-requests.md#best-practices-for-faster-reviews) by Kubernetes (but skip step 0 and 1)
 - Fork the Home Assistant [git repository](https://github.com/home-assistant/core).
 - Write the code for your device, notification service, sensor, or IoT thing.
 - Ensure tests work.
 - Create a Pull Request against the [**dev**](https://github.com/home-assistant/core/tree/dev) branch of Home Assistant.

Still interested? Then you should take a peek at the [developer documentation](https://developers.home-assistant.io/) to get more details.

## Feature suggestions

If you want to suggest a new feature for Home Assistant (e.g., new integrations), please open a thread in our [Community Forum: Feature Requests](https://community.home-assistant.io/c/feature-requests).
We use [GitHub for tracking issues](https://github.com/home-assistant/core/issues), not for tracking feature requests.
=======
# Contribution guidelines

Contributing to this project should be as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features

## Github is used for everything

Github is used to host code, to track issues and feature requests, as well as accept pull requests.

Pull requests are the best way to propose changes to the codebase.

1. Fork the repo and create your branch from `main`.
2. If you've changed something, update the documentation.
3. Make sure your code lints (using `scripts/lint`).
4. Test you contribution.
5. Issue that pull request!

## Any contributions you make will be under the MIT Software License

In short, when you submit code changes, your submissions are understood to be under the same [MIT License](http://choosealicense.com/licenses/mit/) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report bugs using Github's [issues](../../issues)

GitHub issues are used to track public bugs.
Report a bug by [opening a new issue](../../issues/new/choose); it's that easy!

## Write bug reports with detail, background, and sample code

**Great Bug Reports** tend to have:

- A quick summary and/or background
- Steps to reproduce
  - Be specific!
  - Give sample code if you can.
- What you expected would happen
- What actually happens
- Notes (possibly including why you think this might be happening, or stuff you tried that didn't work)

People *love* thorough bug reports. I'm not even kidding.

## Use a Consistent Coding Style

Use [black](https://github.com/ambv/black) to make sure the code follows the style.

## Test your code modification

This custom component is based on [integration_blueprint template](https://github.com/ludeeus/integration_blueprint).

It comes with development environment in a container, easy to launch
if you use Visual Studio Code. With this container you will have a stand alone
Home Assistant instance running and already configured with the included
[`configuration.yaml`](./config/configuration.yaml)
file.

## License

By contributing, you agree that your contributions will be licensed under its MIT License.
>>>>>>> e2d2f1c71c (Initial commit)
