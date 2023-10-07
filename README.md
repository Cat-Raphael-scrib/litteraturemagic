@user-uh2et2do1f # litteraturemagic name: Lint PR
on:
  pull_request_target:
    types: [ opened, edited, synchronize, reopened ]

jobs:
  validate:
    name: Validate title
    runs-on: ubuntu-latest
    steps:
      - uses: amannn/action-semantic-pull-request@v5
        with:
          types: |
            chore
            docs
            fix
            feat
            misc
            test
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }
          .github/CODEOWNERS
          * @electron/wg-ecosystem
          @Cat-Raphael-scrib ➜ /workspaces/valeriehoulejarry (dependabot/npm_and_yarn/electron-26.3.0) $
b9fd90a
