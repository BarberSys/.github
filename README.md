# .github

Shared GitHub configuration and public community files for the BarberSys organization.

This repository contains organization-wide defaults used across BarberSys repositories to keep development workflows simple, consistent and maintainable.

## Purpose

The goal of this repository is to centralize reusable GitHub configuration instead of maintaining the same files independently across multiple repositories.

It currently provides:

- Issue templates
- Pull request templates
- Organization profile content
- Shared public repository conventions

## Structure

```text
.
├── .github/
│   └── ISSUE_TEMPLATE/
│       ├── bug.yml
│       ├── feature.yml
│       └── config.yml
│
├── profile/
│   └── README.md
│
├── PULL_REQUEST_TEMPLATE.md
└── README.md
```

## Issue Templates

### Bug

Used when existing functionality is not behaving as expected.

A good bug report should explain:

- what happened;
- what was expected;
- how to reproduce the problem;
- relevant environment information;
- any useful logs or screenshots.

### Feature

Used for new functionality or meaningful product and engineering improvements.

A good feature request should explain:

- the problem;
- the proposed solution;
- the expected value;
- relevant scope or constraints.

Blank issues are also enabled for cases that do not fit one of the predefined templates.

## Pull Requests

Pull requests should remain focused and easy to review.

Each pull request should clearly explain:

1. what changed;
2. why the change was needed;
3. how the change was tested.

As a general rule, changes should be developed on dedicated branches and merged into the default branch through pull requests.

Examples:

```text
feature/booking-flow
feature/barber-availability
fix/double-booking
fix/timezone-handling
chore/update-dependencies
docs/update-readme
```

## Repository-specific configuration

Repositories may define their own GitHub community files when repository-specific behavior is required.

Repository-level configuration takes precedence over the organization defaults defined here.

## Security

This repository is public.

Do not add:

- credentials;
- API keys;
- secrets;
- internal infrastructure details;
- customer information;
- private operational documentation;
- confidential business information.

Internal BarberSys documentation should be kept in private repositories.

## BarberSys

BarberSys builds modular software for modern barbershops, focused on appointments, operations, customer experience and data-driven business management.
