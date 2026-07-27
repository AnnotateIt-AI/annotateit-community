# Contributing

Thank you for helping improve AnnotateIt. This repository is the public community space for the product: it collects bug reports, feature requests, import and export problems, public release notes and the public roadmap. The AnnotateIt application source code is proprietary and is not hosted here.

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## What is accepted in this repository

Issues:

- reproducible bug reports;
- feature requests and workflow suggestions;
- import and export compatibility problems.

Pull requests:

- corrections and clarifications to the public documents in this repository (`README.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `ROADMAP.md`, `CHANGELOG.md`);
- fixes to issue forms and other community configuration;
- broken links, typos, wording and formatting fixes.

Anything that would change the application itself belongs in an issue, not a pull request.

## What is not accepted

- Application source code, patches to the application, binaries or model weights.
- Decompiled, disassembled or reverse-engineered material of any kind.
- Private datasets, user images, confidential annotations, API keys, license data, unredacted local file paths, full system logs, or personal information.
- Build tooling, dependency manifests, or automation for an application that is not present in this repository.

Content that exposes private or personal data may be removed without notice.

## Opening a good bug report

Use the [bug report form](https://github.com/AnnotateIt-AI/annotateit-community/issues/new?template=bug.yml). A report is actionable when it contains:

- the AnnotateIt version or build, the platform, and the operating system (plus browser and version for the web app);
- the project or task type;
- numbered steps that let someone else reach the same result;
- what you expected, and what happened instead;
- the exact error message, if there was one.

Reproduce the problem on a current build where that is practical, and search the existing issues first. If a sample is needed, use a minimal synthetic or redacted one — you are never required to share your dataset.

For a dataset format problem, use the [import/export form](https://github.com/AnnotateIt-AI/annotateit-community/issues/new?template=import-export.yml) instead; it asks for the format and structure details that make such problems solvable.

## Proposing a feature

Use the [feature request form](https://github.com/AnnotateIt-AI/annotateit-community/issues/new?template=feature.yml). Describe the problem or workflow limitation first and the proposed solution second, and include a concrete use case. Do not include business-sensitive information: a general description of the workflow is enough.

A feature request is not a commitment. Requests are read and weighed against the current product direction, and neither acceptance nor a delivery date is implied.

## Proposing a documentation fix

1. Fork the repository and create a branch.
2. Make the change. Keep the existing tone: plain, professional English, no marketing language.
3. Verify that every link you add or touch resolves, and that the Markdown renders correctly on GitHub.
4. Open a pull request against `main` and complete the checklist in the pull request template.

Please keep pull requests small and focused. A single change with a clear rationale is reviewed far faster than a broad rewrite.

## Accuracy of product claims

Public documents in this repository must describe the product as it actually is. Any statement about a capability, platform, format, price or plan must be verifiable against the [official website](https://annotateit.ai/), the [documentation](https://app.annotateit.ai/docs), or the shipping product. Do not add versions, dates, features or release history that cannot be verified that way.

The [roadmap](ROADMAP.md) describes direction, not commitments. Roadmap items are not promises, carry no dates, and may change or be dropped.

## Security and privacy

Do not report security vulnerabilities in a public issue or pull request. Follow the [security policy](https://annotateit.ai/legal/security/) and email umno.annotateit@gmail.com with "Security report" in the subject.

For privacy questions and requests, email umno.annotateit@gmail.com. See the [privacy policy](https://annotateit.ai/legal/privacy/).

## About the application source

The AnnotateIt application is proprietary and developed in a private codebase. Opening an issue or a pull request here does not grant access to that source, and access will not be provided on request. Because there is no application in this repository, there is nothing to build or install in order to contribute — a text editor is enough.
