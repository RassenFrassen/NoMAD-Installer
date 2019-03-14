# NoMAD-Installer

A script that will install the latest version of NoMAD.app and load the accompanying LaunchAgent.

## Use

This script can be run as a policy in Jamf Pro or run using another management solution.

To run locally:

```
~$ NoMAD.sh
```

The latest version of the NoMAD package will be downloaded, installed and then a LaunchAgent will be written to `/Library/LaunchAgents` and loaded.

* Link to NoMAD package: [https://files.nomad.menu/NoMAD.pkg](https://files.nomad.menu/NoMAD.pkg)
* Link to LaunchAgent documentation: [https://nomad.menu/help-center/automatically-launching-nomad/](https://nomad.menu/help-center/automatically-launching-nomad/)

## Configuration and Management

Learn more about managing NoMAD at [https://nomad.menu/help-center/](https://nomad.menu/help-center/).

If the download URL for NoMAD changes you may use a script parameter to override the hard coded value. For the NoMAD script in your policy, enter the full URL you wish to use in the **"Parameter 4"** field (You may rename the label for this parameter to something more identifiable by going to `Settings > Computer Management > Scripts > the NoMAD script > Options`).
