# Hotwire Example Template

A collection of branches that transmit [HTML over the
wire](https://hotwired.dev).

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)][heroku-deploy-app]

[heroku-deploy-app]: https://heroku.com/deploy?template=https://github.com/thoughtbot/hotwire-example-template/tree/hotwire-example-multi-form-search

## How to read this repository

Through the power of incremental Git diffs, each of this repository's
[branches][] provides a step-by-step demonstration of how to implement a feature
or behavior.

This repository's [main][] branch serves as the root all of the other branches,
and consists of a handful of commits generated by the Rails command line
interface.

Some branches are works-in-progress. Others are more refined. Some noteworthy
branches include:

* [hotwire-example-live-preview](https://github.com/thoughtbot/hotwire-example-template/tree/hotwire-example-live-preview)
* [hotwire-example-typeahead-search](https://github.com/thoughtbot/hotwire-example-template/tree/hotwire-example-typeahead-search)
* [hotwire-example-tooltip-fetch](https://github.com/thoughtbot/hotwire-example-template/tree/hotwire-example-tooltip-fetch)
* [hotwire-example-stimulus-dynamic-forms](https://github.com/thoughtbot/hotwire-example-template/tree/hotwire-example-stimulus-dynamic-forms)
* [hotwire-example-turbo-dynamic-forms](https://github.com/thoughtbot/hotwire-example-template/tree/hotwire-example-turbo-dynamic-forms)

A branch's [README.md](./README.md) includes a prose explanation of the patterns
at-play. When reading a branch's source code, read the changes commit-by-commit
either on the branch comparison page (for example,
[main...hotwire-example-live-preview][]), the branch's commits page (for
example, [hotwire-example-live-preview][]), or the branch's `README.md` file
(for example, [hotwire-example-live-preview][README]).

To experiment with a branch on your own, clone the repository, check out the
branch, execute its set up script, start the local server, then visit
<http://localhost:3000>:

```sh
bin/setup
bin/rails server
open http://localhost:3000
```

[branches]: https://github.com/thoughtbot/hotwire-example-template/branches/all
[main]: https://github.com/thoughtbot/hotwire-example-template/tree/main
[main...hotwire-example-live-preview]: https://github.com/thoughtbot/hotwire-example-template/compare/hotwire-example-live-preview
[hotwire-example-live-preview]: https://github.com/thoughtbot/hotwire-example-template/commits/hotwire-example-live-preview
[README]: https://github.com/thoughtbot/hotwire-example-template/blob/hotwire-example-live-preview/README.md

## How to fork this repository

⚠️ If you're hoping to fork this repository and periodically pull down upstream
changes, you're going to have a Bad Time. ⚠️

Each branch builds its narrative through incremental changesets that are
visualized as Git diffs. It's not uncommon for code revisions to be made after a
branch is published. Changes are retroactively incorporated into the most
appropriate commit available. In fact, histories are [rebased][] and rewritten
on a regular basis. In practice, these deviations from conventional Git
workflows make this repository a bad candidate for forking.

With that being said, if you're comfortable with [interactive rebasing][], the
[CONTRIBUTING.md](./CONTRIBUTING.md) guide outlines some of the commands and
procedures used to create this repository's content.

[rebased]: https://git-scm.com/book/en/v2/Git-Branching-Rebasing
[interactive rebasing]: https://git-scm.com/docs/git-rebase#Documentation/git-rebase.txt---interactive
