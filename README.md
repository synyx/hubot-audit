# hubot-audit

log all hubot interaction to an audit channel
We found this helpful to audit hubot history in one central place, including commands issued in multiple channels.
We recommend setting the channel mode to 'moderated', so that no additional noise, comments and catpics get (accidently) added there.

See [`src/audit.coffee`](src/audit.coffee) for full documentation.

## Installation

# for now, copy src/audit.coffee to your hubot/scripts folder until the module gets included in nodejs repos

In hubot project repo, run:

`npm install hubot-audit --save`

Then add **hubot-audit** to your `external-scripts.json`:

```json
[
  "hubot-audit"
]
```

## Sample Interaction
None, bot will passively log all interaction

