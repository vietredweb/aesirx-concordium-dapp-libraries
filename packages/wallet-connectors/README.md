name: Build, test, and upload release [placeholder]

on:
    workflow_dispatch: # trigger manually
        inputs:
            tag_override:
                description: "Tag"
                type: string
                required: false
            # TODO Extract from appropriate changelog.
            release_notes:
                description: "Release notes"
                type: string
                required: true

jobs:
  dummy:
        runs-on: ubuntu-latest
        steps:
          - run: echo placeholder