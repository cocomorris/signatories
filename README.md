# Signing the Whirlpool Manifesto
Sign the [Whirlpool Manifesto](https://whirlpoolmanifesto.org) by creating a pull request in this repository. Your PR should contain a new JSON file in the /signatories folder. Make sure the filename is unique (it should include your name and the date signed) and carefully follow the format described below.

After the PR is approved, your signature should be included at [whirlpoolmanifesto.org/signatories](https://whirlpoolmanifesto.org/signatories) within approximately 8 hours. 

## Signature File Naming Convention

`<Full-Name-Here>_<YYYY-MM-DD>.json`

Example: `Joe-Blow_2021-01-15.json` - for Joe Blow, signed on January 15th, 2021.

Use dashes to separate your first and last name, initials, and identifiers. Names can include capitalization.
To discern between you and someone with the same full name - you may want to include a middle name, middle initial(s), or company after your name.

Example: `Joe-F-Blow-SomeCompany_2021-01-15.json`.

## Signature File Format

A signature file should contain your full name (required), date of signing (required), and optionally a personal homepage (such as a GitHub page or Twitter account) and a quick professional profile.

```JSON
{
  "fullName": "<full_name_here>",
  "date": "<YYYY-MM-DD>",
  "homepage": "<homepage_full_url_here>",
  "profile": "<some_description_about_you_here>"
}
```

Example:
```JSON
{
    "fullName": "Joe Blow",
    "date": "2021-01-29",
    "homepage": "https://github.com/joebow",
    "profile": "Joe Blow is a C++ dev for over 30 years and has done incredible work..."
}
