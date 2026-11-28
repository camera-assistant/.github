# Contributing to Camera Assistant

Thank you for wanting to help. The project has just started, so these rules are short and will grow.

The plans are in the [backlog](https://github.com/camera-assistant/backlog/tree/main/docs/plans) and the design is described in the [architecture](https://github.com/camera-assistant/backlog/blob/main/docs/architecture.md). The open tasks are on the [project board](https://github.com/orgs/camera-assistant/projects/2).

## Start from an issue

- Pick a task that has nobody assigned, and say in a comment that you are taking it.
- An idea or a change that is not on the board starts as a [discussion](https://github.com/camera-assistant/backlog/discussions/categories/ideas), so it can be talked through before you start.
- A change to a design starts as a pull request to the plan in the backlog.
- Report a bug in the repository it concerns: [camera-assistant](https://github.com/camera-assistant/camera-assistant/issues) for the server, [frontend](https://github.com/camera-assistant/frontend/issues) for the web interface.

## Pull requests

- One issue per pull request, and keep it small.
- Link the issue in the description with its full address, such as `Closes https://github.com/camera-assistant/backlog/issues/<n>`, and name the plan step it implements.
- Tests come with the change. A bug fix comes with a test that fails without the fix.
- Design reasoning goes into the plan or the pull request description, not into private notes.
- A maintainer reviews every change before it is merged.

## Coding agents

Contributions written with a coding agent are welcome. The person who opens the pull request has read the change, has run it, and answers for it like for their own code.

## Licences

- New dependencies may only use one of these licences: Apache-2.0, MIT, BSD-2-Clause, BSD-3-Clause, ISC, Zlib, Unicode-3.0, or a combination of these.
- A new licence is added to that list in its own pull request, with the reason in the description.
- Where a module uses FFmpeg, it uses a build without the GPL parts (no `--enable-gpl`).
- A model file that the project ships or downloads needs an entry in the model manifest (`models/models.toml`), and its licence must be Apache-2.0 or MIT.
- Closed vendor runtimes never enter the main repository or the server image. They belong in a repository for that kind of hardware.

Contributions are licensed under the Apache License 2.0, like the rest of the project.

## Security

Do not report a security problem in a public issue. See [SECURITY.md](SECURITY.md) for how to report it privately.
