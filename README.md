# Rust server hello world app

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

This simple application is intended to serve as an example of:
- how to use Rust to build a web backend server
- how to containerize the application
- how to build a CI/CD pipeline for the application
- how to automate everything with ansible (maybe)

Links to
- [Trello board](https://trello.com/b/VOUJruh8/hello-world)
- [GitHub repo](https://github.com/martin-hanekom/hello-world)

### Web framework research

Many different Rust web frameworks exist, and even though some are more popular than others, the community is far from a consensus. Sylvian Kerkour compares three common frameworks [here](https://kerkour.com/rust-web-framework-2022).

Even though `actix-web` is extremely popular, I'm going to try `axum` as a light-weight, modular choice.
