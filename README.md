# Signatures

Email signatures for Fire and Lean team members.

## Usage

To get your signature, visit [the website](https://fireandlion.github.io/signatures/) and select your name. Then Ctrl+A/Cmd+A to select all, and copy-paste the signature into your email program's signature field or into individual messages.

Email programs will display signatures differently. You may see slightly different things in different browsers. The aim is that the signature should never look awful.

If you do find an awful rendering in an email program, please take a screenshot and log an issue here with details of the email program and device it was on.

## Changing personal details

To change personal details in a signature (e.g. name or phone number), edit the values in the `_data/team.yml` file.

To create a new person's signature, add their details to `_data/team.yml` and create a markdown file for them alongside the others. The filename should match the `file` value, and the file should contain:

```
---
---
{% include signature %}
```

## Changing the signature

### Template

The template for the signature is an HTML table in `_includes/signature`. That's inserted into a full HTML document in `_layouts/default.html`. The HTML document is compressed by `_layouts/compress.html`.

### Font

We link to a webfont from the HTML `head`, but as a backup provide a font stack of fonts we consider acceptable.

### Logo

We link to the online, absolute URL of the logo, so that it isn't an attachment in the email.

### Why not base64?

We tried encoding the font and image as base64, but Gmail says the signature is too long. A pity, it was neat!
