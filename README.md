<!--
SPDX-FileCopyrightText: 2020 The HedgeDoc developers (see AUTHORS file)

SPDX-License-Identifier: CC-BY-SA-4.0
-->

# HedgeDoc website

This repository contains the source for the [homepage](https://ev.hedgedoc.org)

## Development

You'll need:

- [Hugo](https://gohugo.io/)
  
  Please make sure, that you use hugo extended! The code won't compile with the default hugo. If you're not sure about the version, run `hugo version` and check the output for the `/extended` suffix after the version.
- NodeJS (LTS or current version)
  
  Run `npm install`. Our package configuration will take care of everything else.

To start the dev server just run `hugo server`.

## License
Licensed under Creative Commons Attribution Share Alike 4.0 International.

The license does not include the HedgeDoc logo, whose terms of usage can be found in the [github repository](https://github.com/hedgedoc/hedgedoc-logo).
