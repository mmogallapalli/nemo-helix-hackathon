<!-- SPDX-FileCopyrightText: Copyright (c) 2025-2026 NVIDIA CORPORATION & AFFILIATES. All rights reserved. -->
<!-- SPDX-License-Identifier: Apache-2.0 -->

# Contributor quick start

Welcome! Before making a change, follow the repository's [setup guide](SETUP.md) and review the full [contribution guide](CONTRIBUTING.md) for the development workflow and project requirements.

## Prepare a focused change

- Create a branch from the latest `main` branch.
- Give the change one clear purpose and keep the diff as small as practical.
- Avoid unrelated refactors, formatting changes, or generated files.
- Use clear commits that describe what changed and include the required DCO sign-off.

## Describe validation in your pull request

List the commands or manual checks you performed, along with their results. Choose checks that match the files and behavior you changed. If a check was not run or has a known gap, say so and explain why.

For example:

- `make check-copyright-headers` — passed.
- Reviewed the rendered Markdown and confirmed that its links resolve.
- Full test suite not run because the change only updates documentation.
