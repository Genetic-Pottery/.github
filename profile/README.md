# Genetic Pottery

Experimental tooling. Things built to answer a question about how software
should feel to work on, taken far enough to find out.

Nothing here is trying to be the standard way to do anything. If it were, it
would already exist somewhere else and would be used instead. What lands here is
the stuff with an odd shape — ideas that only make sense once you've lived with
them for a week, and that would get sanded flat by any attempt to make them
normal first. Some of it will turn out to be useful to other people. That is a
happy outcome rather than the plan.

## What's here

- **[warlock](https://github.com/Genetic-Pottery/warlock)** — A Claude Code plugin that keeps AI inside the code your team owns.
  Each team's directories are a scope tied to its Linear team or Jira project.
  An agent works only from a ticket, changes only that team's files, and ends in
  a pull request or a halted ticket that says why.
- **[warlock-deploy](https://github.com/Genetic-Pottery/warlock-deploy)** — A cloud-hosted setup for warlock. An always-on Claude instance you can
  remote-control into to complete tasks. Terraform and NixOS on EC2.
- **[migcheck](https://github.com/Genetic-Pottery/migcheck)** — Checks that a release's database migrations don't break the release
  running in production. It replays the old release's queries against the new
  schema, the way they run during a rolling deploy or after a rollback.
  Supports Postgres and MySQL.
