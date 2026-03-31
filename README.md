# All-Custom-Field-Types

The purpose of this project is to easily enable testing for all custom field types for the TaskRay Project, TaskRay Task, and TaskRay Task Group objects.

## Fields included
- Auto Number
- Formula
- Roll-up Summary
- Lookup Relationship
- Checkbox
- Currency
- Date
- Date/Time
- Email
- Geolocation
- Number
- Percent
- Picklist
- Picklist (Multi-Select)
- Text
- Text Area
- Text Area (Long)
- Text Area (Rich)
- Text (Encrypted)
- Time
- URL

## Fields not included
- Master-Detail Relationship
- External Lookup Relationship

## Steps

1. Connect your 2GP org to Visual Studio Code using 'SFDX: Authorize An Org' in the command pallette
2. Right-click 'package.xml' (in manifest directory) and select 'SFDX: Deploy Source in Manifest to Org'
3. Assign 'QA TaskRay All Custom Field Types' Perm Set to your User which grants Read and Edit field perms

## Read All About It

- [Salesforce Extensions Documentation](https://developer.salesforce.com/tools/vscode/)
- [Salesforce CLI Setup Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm)
- [Salesforce DX Developer Guide](https://developer.salesforce.com/docs/atlas.en-us.sfdx_dev.meta/sfdx_dev/sfdx_dev_intro.htm)
- [Salesforce CLI Command Reference](https://developer.salesforce.com/docs/atlas.en-us.sfdx_cli_reference.meta/sfdx_cli_reference/cli_reference.htm)
