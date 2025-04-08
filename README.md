# Post development updates to the #trackydev OTN Slack channel

This is a [custom composite GitHub action](https://docs.github.com/en/actions/sharing-automations/creating-actions/about-custom-actions#about-custom-actions) 
used in [trackyverse](https://github.com/trackyverse) development to notify members of the OTN #trackydev Slack channel. It requires the 
webhook of the Slack Application provided via a secret to the `bot-token` argument.
[See an example here](https://github.com/trackyverse/ATO/blob/45bb104bc8cec8a253c92391a9f564b5838db90f/.github/workflows/alert-slack.yaml#L14-L15).
