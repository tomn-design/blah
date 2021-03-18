---
description: >-
  Huddle provides and integration with Slack for attendee messaging and
  conference wide communications.
---

# Slack Integration

### Setup <a id="setup"></a>

In order to setup the slack integration please install our Slack application into your Slack workspace using the button below.[![Add to Slack](https://platform.slack-edge.com/img/add_to_slack.png)](https://slack.com/oauth/v2/authorize?client_id=1692828468469.1708547553937&scope=&user_scope=users:read,users:read.email)

Once you have approved the Slack application install you will end up on a page like this:![](https://docs.huddle.thinkactivelabs.co.uk/slack-token-screen.png)

Please provide the token on this screen to your Huddle account manager. To complete the integration setup!

### Using the integration <a id="using-the-integration"></a>

The Slack integration forms two parts. Our integration, now enabled, allows attendees to message workshop organisers and other attendees with links to Slack.

Slack buttons will only appear on the Huddle platform once the logged in user has signed up to the linked Slack group.

#### Attendee List Integration <a id="attendee-list-integration"></a>

If you have our Attendee list funtionality then as your attendees join the Huddle conference and Slack they will be have a new button appear on their Attendee card.![](https://docs.huddle.thinkactivelabs.co.uk/slack-attendee-message.png)

Attendee email addresses in Huddle must match their email address within the event Slack Workspace for the Slack integration to function.

#### Session Integration <a id="session-integration"></a>

During sessions the Slack integration takes two forms.

* Session Slack Channels
* Contact Host on Slack

**Configuration**

These channels and host contact mechanisms must be configured using the Huddle Content editor. You must configure the following fields on the Session editor:![](https://docs.huddle.thinkactivelabs.co.uk/netlify-slack-session.png)

You can find your Slack User ID by opening Slack by:

1. Navigate to `Profile & account` from the dropdown from the workspace name
2. Click the `...` for more actions
3. And click copy `Member ID`

This ID should look something like `U01L145CDM5`

You do not have to configure both of these properties. If you do not require a Slack Channel/Host Contact on Slack for a session simply do not conifigure one and no Slack buttons will show for that session.

Ensure that when adding a Slack Channel to a Session you do not include the `#`this will break the link.

The linked Slack channel must exist for this link to work. Linking to channels that do not exist will cause an error.

**Using Slack in a Session**

Attendees can participate in the configured Slack channel for the session by clicking the sidebar button `Open Slack Channel`. This will open Slack at the channel for the session.![](https://docs.huddle.thinkactivelabs.co.uk/slack-session-channel.png)

Attendees can contact the session host via Slack sidebar button `Contact Host on Slack`. This will open Slack with a direct message to the session organiser.![](https://docs.huddle.thinkactivelabs.co.uk/slack-session-host.png)

