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
  buf: .github/taskfiles/Buf.yml
  bun: .github/taskfiles/Bun.yml
  docker: .github/taskfiles/Docker.yml
  dokku: .github/taskfiles/Dokku.yml
  doppler: .github/taskfiles/Doppler.yml
  genesis: .github/taskfiles/Genesis.yml
  gh: .github/taskfiles/Gh.yml
  go: .github/taskfiles/Go.yml
  goreleaser: .github/taskfiles/Goreleaser.yml
  json: .github/taskfiles/Json.yml
  log: .github/taskfiles/Log.yml
  pkl: .github/taskfiles/Pkl.yml
  templ: .github/taskfiles/Templ.yaml
  wrangler: .github/taskfiles/Wrangler.yml
```
