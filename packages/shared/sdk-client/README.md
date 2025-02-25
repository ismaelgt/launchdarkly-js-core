# LaunchDarkly SDK JavaScript Common Client Code

[![NPM][js-client-sdk-common-npm-badge]][js-client-sdk-common-npm-link]
[![Actions Status][shared-sdk-client-ci-badge]][shared-sdk-client-ci]
[![Documentation][shared-sdk-client-ghp-badge]][shared-sdk-client-ghp-link]

> [!CAUTION]  
> This package is for internal use only. Do not use it directly.

This project contains Typescript classes and interfaces that are applicable to client-side SDKs.

This library is a beta version and should not be considered ready for production use while this message is visible.

## Contributing

See [Contributing](../CONTRIBUTING.md).

## About LaunchDarkly

- LaunchDarkly is a continuous delivery platform that provides feature flags as a service and allows developers to iterate quickly and safely. We allow you to easily flag your features and manage them from the LaunchDarkly dashboard. With LaunchDarkly, you can:
  - Roll out a new feature to a subset of your users (like a group of users who opt-in to a beta tester group), gathering feedback and bug reports from real-world use cases.
  - Gradually roll out a feature to an increasing percentage of users, and track the effect that the feature has on key metrics (for instance, how likely is a user to complete a purchase if they have feature A versus feature B?).
  - Turn off a feature that you realize is causing performance problems in production, without needing to re-deploy, or even restart the application with a changed configuration file.
  - Grant access to certain features based on user attributes, like payment plan (eg: users on the ‘gold’ plan get access to more features than users in the ‘silver’ plan). Disable parts of your application to facilitate maintenance, without taking everything offline.
- LaunchDarkly provides feature flag SDKs for a wide variety of languages and technologies. Check out [our documentation](https://docs.launchdarkly.com/sdk) for a complete list.
- Explore LaunchDarkly
  - [launchdarkly.com](https://www.launchdarkly.com/ 'LaunchDarkly Main Website') for more information
  - [docs.launchdarkly.com](https://docs.launchdarkly.com/ 'LaunchDarkly Documentation') for our documentation and SDK reference guides
  - [apidocs.launchdarkly.com](https://apidocs.launchdarkly.com/ 'LaunchDarkly API Documentation') for our API documentation
  - [blog.launchdarkly.com](https://blog.launchdarkly.com/ 'LaunchDarkly Blog Documentation') for the latest product updates

[js-client-sdk-common-npm-badge]: https://img.shields.io/npm/v/@launchdarkly/js-client-sdk-common.svg?style=flat-square
[js-client-sdk-common-npm-link]: https://www.npmjs.com/package/@launchdarkly/js-client-sdk-common
[shared-sdk-client-ci-badge]: https://github.com/launchdarkly/js-core/actions/workflows/sdk-client.yml/badge.svg
[shared-sdk-client-ci]: https://github.com/launchdarkly/js-core/actions/workflows/sdk-client.yml
[shared-sdk-client-ghp-badge]: https://img.shields.io/static/v1?label=GitHub+Pages&message=API+reference&color=00add8
[shared-sdk-client-ghp-link]: https://launchdarkly.github.io/js-core/packages/shared/sdk-client/docs/
