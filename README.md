# templates-and-tools

A template repository with multiple automations

## Actions / Workflows

### Stale Issue Manager

Based off: [/actions/close-stale-issues](https://github.com/marketplace/actions/close-stale-issues)

Runs every day at 12PM and

- Labels issues with 60+ days of inactivity with: LINK TO LABEL
-

Exempted Labels

Stale Messages
Issue
PR

### Notifications

#### Post Slack Message

[Slack Message](https://github.com/abinoda/slack-action)

## Label Manager

[EndBug/label-sync](https://github.com/EndBug/label-sync)

[/a11ywatch/github-actions](/a11ywatch/github-actions)

# NEWS

# github-label-manager

To sync and manage the labels I use

## Label Groups

| **Defaults**                                        | Points                                                              | Status | Type                                         | State                                                      |
| --------------------------------------------------- | ------------------------------------------------------------------- | ------ | -------------------------------------------- | ---------------------------------------------------------- |
| Standard labels commonly used in most repositories. | Describes the relative effort to complete an issue or pull request. | df     | Describes the type of issue or pull request. | Describes the decision state of the issue or pull request. |

| Label                                                                                  | Color     | Description | Alias |
| -------------------------------------------------------------------------------------- | --------- | ----------- | ----- |
| https://github.com/TheBoatyMcBoatFace/github-label-manager/labels/good%20first%20issue | `#5319e7` | ids         | asl   |

## Inspiration

The [Label Sync](https://github.com/marketplace/actions/label-sync) Github Action by @EndBug

Label Exporter - https://github.com/marketplace/actions/export-label-config

---

- name: A label
  color: '000000'

- name: Another label
  color: '111111'
  description: A very inspiring description

- name: Yet another label
  color: '222222'
  aliases: ['first', 'second', 'third']

https://github.com/actions/stale

https://github.com/actions/labeler

Auto stale issues
manage github labels
auto-tag commits based on where the code is going
auto-tag issues
issue form templates

[issue-label-manager-action](https://github.com/lannonbr/issue-label-manager-action)

[Awesome Github Actions](https://github.com/sdras/awesome-actions)

^^^

### Projects

- [Automate Project Cards based on issues & pull requests](https://github.com/alex-page/github-project-automation-plus)
- https://github.com/alex-page/github-project-automation-plus

[Create Issue from File Content](https://github.com/peter-evans/create-issue-from-file)

[Label Pull Requests based on committed files](https://github.com/Decathlon/pull-request-labeler-action)

[Tag issues with labels based on rules](https://github.com/damccorm/tag-ur-it)

[Labels issues based on body content](https://github.com/Renato66/auto-label)

[Sync to external repo](https://github.com/kai-tub/external-repo-sync-action)

[Action Badges](https://github.com/atrox/github-actions-badge)

[Github Actions](https://github.com/orgs/actions/repositories?type=all)

https://github.com/actions/starter-workflows

[Github Actions Badge](https://actions-badge.atrox.dev/)

[Github Actions Hub](https://github.com/actionshub)
[Run Lighthouse Check on Website](https://github.com/jakejarvis/lighthouse-action)

### Action Branding

[Docs](https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions#branding)
[Github Actions Branding Cheat Sheet](https://haya14busa.github.io/github-action-brandings/)

[Workflow Syntax](https://docs.github.com/en/enterprise-server@3.3/actions/using-workflows/workflow-syntax-for-github-actions)

### Interesting, but not super useful for us

- https://github.com/siderolabs/conform
- [Codeowners File Validation](https://github.com/mszostok/codeowners-validator)
