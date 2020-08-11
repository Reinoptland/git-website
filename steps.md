## How to git "gud"

## Setup

- `git init`
- Initial commit (with a readme, or a scaffold) on master
- Add remote (repo on github, link the two)
- Push to master (one time)

## Make a development branch

- `git checkout -b development`
- `git push origin development`
- go to github, make development your `default` branch

## How to use a feature branch

- Start from development
- `git checkout development`
- (optional) pull updates from origin (maybe your colleagues did some work)
- `git pull origin development`
- Make a new feature branch
- `git checkout -b branch-name`
- Code / Hack / Style etc..
- Commit your work
- Push to github
- `git push origin branch-name`
- Make a pullrequest (with a summary)
- Ask review
- Merge the pullrequest
