<!--
  ~ SPDX-License-Identifier: Apache-2.0
-->

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="images/rackmarshal-lockup-dark.svg">
    <img src="images/rackmarshal-lockup.svg" alt="Rackmarshal" width="600">
  </picture>
</p>

## Infrastructure management

Rackmarshal manages servers, network infrastructure devices, and other remote endpoints. A
desired-state authority owns the directives describing how an endpoint should be configured and
reconciles them against what it reports — enforcing agentless devices directly, and handing
directives to an on-host agent wherever one can run.

The system is built as microservices. This organization is where those service, library, and
tooling repositories live; they are being stood up now.

## Documentation

Project documentation, design records, and the website live in
[`servercurio/rackmarshal`](https://github.com/servercurio/rackmarshal). The
[design documents](https://github.com/servercurio/rackmarshal/tree/main/docs/design) cover the
repository plan, the service boundaries, the desired-state model, and the brand.

## License

Rackmarshal is licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
