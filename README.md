# AWS Baseline

Defines esssential baseline resources that should exist in every AWS account.
This project is intended to be a combination of best practices documentation
with a step-by-step guide on setting up an AWS account in A Right Way™ (or at
least that's what I'm calling it).

To assist in implementing these practices, they have been codified as much as
possible with Terraform. I hope to add more provisioning options in the future,
as this project continues to move towards providing a set of structured data
that can be consumed by various tooling, for the most truest sense of freedom.

## Maturity

This project is a work in progress. Don't expect anything to be functional. You
are owed NOTHING! But we're going to follow semver once things are rolling.

## Documentation

You can view the doc on [GitHub Pages]. The Markdown sources are all in the
[docs] directory.

## Building the Docs

Requirements:

- Poetry: This project uses poetry for managing Python requirements
- make: Used for convenience in building/deploying the docs

A static site is generated from the Markdown sources by using mkdocs. To build,
a simple `make build` should do.

To run a local server that will auto-generate and reload the static site when
the Markdown sources or mkdocs configs are modified. Use `make serve` to run
it, and access it on https://localhost:3000

## Contributing

View the [Contributing Guide] if you're interested in. . . contributing. Check
out the [Code of Conduct] while you're at it.

## License

This project uses the [MIT License].


<!-- Markdown Anchors -->
[GitHub Pages]: https://timoguin.github.io/aws-baseline
[docs]: https://github.com/timoguin/aws-baseline/tree/master/docs
[Contributing Guide]: .github/CONTRIBUTING.md
[Code of Conduct]: .github/CODE_OF_CONDUCT.md
[MIT License]: .github/LICENSE.md
