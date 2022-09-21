# GERP

# Goal
We are on a mission to reduce tedious, manual maintenance Pull Requests for Open-Source GitHub repositories.

In maintaining the Azure Kubernetes Service Github Actions, we found ourselves making edits across over a dozen repos that each held an action.

While local scripting could work around this, we wanted a way to keep the templates for things like bug reports and issues synchronized across our repos, and easily copied into new repos without hacky scripts.

For the Microsoft 2022 Hackathon we decided to create GERP to solve this problem.

GERP uses a single template repo to synchronize repository templates via batch Pull Requests

# How-to
You can get started over at the (GERP repo)[https://github.com/gerp-project/gerp]
