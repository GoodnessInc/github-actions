# github-actions

Actions shared by many projects.  Ported from https://github.com/BKWLD/cloak-actions.

## Usage

Add the following to a step:

```
jobs:
  job_name:
    runs-on: ubuntu-latest
    steps:
      - uses: GoodnessInc/github-actions/install@v3
        # The following is optional
        with:
          cwd: packages/ugc-housekeeper
```
