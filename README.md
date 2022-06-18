# Conclude Apps

This directory contains Conclude smart workflow templates for Slack. These apps can be used out of the box, or
customized for your team.

Prerequisites:
- Make sure that Conclude has been installed in your team's Slack workspace.
- Check if Conclude is already installed by typing the Slack command `/c help`, or locate Conclude under Apps in the sidebar.
- To install Conclude, go to https://conclude.app and click [Sign In](https://conclude.app/signin).

To install an app in your Slack team.
- In Slack, type the command `/c app install`, or install from Conclude Home > Apps.
- You can choose from a list, or specify the app on the command line: `/c app install support`

You can also install apps directly from other public GitHub repositories (use the full URL).

| App                                             | Name                | Description                                   |
|-------------------------------------------------|---------------------|-----------------------------------------------|
| [generic.yaml](/generic.yaml)                   | Generic template    | A generic app                                 |
| [minimal.yaml](/minimal.yaml)                   | Minimal template    | A minimal app with only a subject field       |
| [incident.yaml](/incident.yaml)                 | Incident management | Manage and resolve incidents                  |
| [bug.yaml](/bug.yaml)                           | Bug tracking        | Report and track bugs                         |
| [support.yaml](/support.yaml)                   | Support system      | For customer support or in-house use          |
| [helpdesk.yaml](/helpdesk.yaml)                 | Helpdesk ticketing  | Similar to support, but with a category field |
| [jira.yaml](/jira.yaml)                         | Jira integration    | Manage Jira issues in Slack                   |
| [approval.yaml](/approval.yaml)                 | Approval            | Request for approval                          |
| [decision.yaml](/decision.yaml)                 | Decision            | Decision-making in Slack                      |
| [decision-options.yaml](/decision-options.yaml) | Decision options    | Make a decision from a list of options        |
| [contact-form.yaml](/contact-form.yaml)         | Contact form        | Handle webform contact requests               |

For more information about Conclude apps, please visit
the Conclude [developer's guide.](https://conclude.app/doc/developer/)
