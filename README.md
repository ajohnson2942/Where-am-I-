# Where Am I? prototype

A small status website with only three settings:

- Location: On Campus, Off Campus, or In My Room
- If in room: Sleeping, Homework / Club Stuff / Something Important, or Chilling
- Do Not Disturb: Yes or No

## Pages

- Public status: `https://ajohnson2942.github.io/where-am-I-/`
- Phone updater: `https://ajohnson2942.github.io/where-am-I-/update.html`
- Printable door sign: `https://ajohnson2942.github.io/where-am-I-/door-sign.html`

## One-time phone setup

The update page writes to `status.json` through the GitHub Contents API. Create a fine-grained personal access token that can access only the `where-am-I-` repository and give it `Contents: Read and write` permission. Paste it into the update page once; it is stored in that phone's browser.

The public page does not need a login and cannot edit the status.
