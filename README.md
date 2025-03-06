# Taskfiles

## Installation

In a repository with a `.github` folder, run:

```bash
rm -rf .github/taskfiles
git clone https://github.com/onsonr/taskfiles.git ./.github/taskfiles
rm -rf ./.github/taskfiles/.git README.md
```

## Usage

Add the following to the `Taskfile.yml` file at the root of your repository:

```yaml
includes:
  buf: .github/taskfiles/Taskfile.buf.yml
  bun: .github/taskfiles/Taskfile.bun.yml
  docker: .github/taskfiles/Taskfile.docker.yml
  dokku: .github/taskfiles/Taskfile.dokku.yml
  doppler: .github/taskfiles/Taskfile.doppler.yml
  gh: .github/taskfiles/Taskfile.gh.yml
  go: .github/taskfiles/Taskfile.go.yml
  goreleaser: .github/taskfiles/Taskfile.goreleaser.yml
  log: .github/taskfiles/Taskfile.log.yml
  pkl: .github/taskfiles/Taskfile.pkl.yml
  templ: .github/taskfiles/Taskfile.templ.yaml
  wrangler: .github/taskfiles/Taskfile.wrangler.yml
```
