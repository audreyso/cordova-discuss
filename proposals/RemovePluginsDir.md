# Remove Plugins Directory
- Status: Proposed

## Overview
This is a proposal to remove the plugins directory. [See issue CB-13059](https://issues.apache.org/jira/browse/CB-13059)

## Current
With cordova-fetch, all modules are saved in node_modules directory directly.
Our code currently copies the plugin folder from a projects node_modules into plugins directory of a project. And then the plugin gets copied from the plugins directory into the specific platform.

## Proposal
This proposal recommends removing the need to stage plugins in the plugins directory and copy it straight from node_modules into platforms directory when it gets installed.

## Additional Work

## Links
[CB-13059](https://issues.apache.org/jira/browse/CB-13059)