# Examples

This repo holds example Rein programs. The [rein](https://github.com/rein-lang/rein) tests use it as a submodule. Its `rein/` folder holds the example programs, one folder per program, each with a `rein.json` manifest.

Each example has a page on the docs site: [rein-lang.com/docs/examples](https://rein-lang.com/docs/examples/). Read more about Rein at [rein-lang.com](https://rein-lang.com).

- [merge-pr](rein/merge-pr): checks a pull request and picks the next step. Shows a retry that starts the program again.
- [incident-triage](rein/incident-triage): route a production alert to a page, a runbook, or a ticket.
- [support-ticket](rein/support-ticket): route a customer ticket. Shows a template and an async request.
- [pr-handling](rein/pr-handling): one pull request. Takes the link as the input `pr` and passes it on.
- [priority-work](rein/priority-work): finds the high priority projects, then works on their pull requests. Shows a call with return (`await findProjects(...)`).

Run `rein list` from here to list them:

```sh
cd examples  # this repo root
rein list
rein run support-ticket
```
