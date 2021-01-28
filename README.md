# Signing the Whirlpool Manifesto
Sign the [Whirlpool Manifesto](https://whirlpoolmanifesto.org) by creating a pull request in this repository. Your PR should contain a JSON file in the /signatories folder. Make sure the filename is unique (it should include your name and the date signed) and follows the format described below.

After the PR is approved, your signature should be included in the site within a few days. 

## Signature File Naming Convention

`<full-name-here>_<YYYY-MM-DD>.json`
Example: `Joe-Blow_2021-01-15.json` - For Joe Blow, signed on January 15th, 2021.

Use dashes to separate your first and last name, initials, and identifiers.
To discern between you and someone with the same full name - you may want to include a middle name, middle initial(s), or company after your name.

Example: `Joe-F-Blow-SomeCompany_2021-01-15.json`.

## Signature File Format

A signature file should contain your full name (required) and optionally a personal homepage (such as a GitHub or Twitter profile) and a quick professional profile.

```JSON
  "fullName": "<full_name_here>",
  "homepage": "<homepage_full_url_here>",
  "profile": "<some_description_about_you_here"
```

